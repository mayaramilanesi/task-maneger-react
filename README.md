# Task Manager React App

This is a simple task management application built with React and Vite. The app allows users to add, view, complete, and delete tasks. It utilizes local storage to persist tasks and fetches sample tasks from an external API.

## Features

- Add new tasks with a title and description.
- View a list of tasks with their completion status.
- Mark tasks as completed or delete them.
- View task details on a separate page.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A build tool that provides a fast development environment.
- **Lucide React**: A collection of icons for React.
- **UUID**: A library for generating unique identifiers.
- **React Router**: For handling routing in the application.
- **Tailwind CSS**: A utility-first CSS framework for styling.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd task-manager-react
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and go to `http://localhost:3000` to view the application.

## Usage

- **Adding a Task**: Enter a title and description in the input fields and click the "Add" button.
- **Viewing Tasks**: The tasks will be displayed in a list format. Click on a task to view its details.
- **Completing a Task**: Click on the task title to toggle its completion status.
- **Deleting a Task**: Click the trash icon next to a task to delete it.

## File Structure

src/
├── components/
│ ├── AddTask.jsx
│ ├── Button.jsx
│ ├── Input.jsx
│ ├── Tasks.jsx
│ └── Title.jsx
├── pages/
│ └── TaskPage.jsx
├── App.jsx
├── main.jsx
├── index.css
└── App.css

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is open-source and available under the [MIT License](LICENSE).
