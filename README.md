# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

---

# Simple To-Do Application

This is a simple To-Do application that allows users to add, update, delete, and mark tasks as completed. The app is designed to be lightweight and easy to use, perfect for basic task management.

## Features

- Add new tasks
- View a list of tasks
- Mark tasks as completed
- Edit task descriptions
- Delete tasks

## Technologies Used

- Frontend: HTML, CSS, JavaScript ,framework - React
- Backend: Node.js 
- Database: JSON (in-memory) / LocalStorage (for browser-based app)
- Other tools: NPM.

---

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [License](#license)

---

## Installation

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (if a backend is used)
- A code editor (VS Code, Sublime, etc.)
- Git (optional, for cloning the repository)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/simple-todo-app.git
   ```

2. Navigate into the project directory:

   ```bash
   cd simple-todo-app
   ```

3. Install dependencies (if applicable):

   ```bash
   npm install
   ```

4. Run the application:

   - **Frontend only:**
     Open `index.html` in your browser.

   - **Node.js (Backend included):**
     Start the backend server:
     ```bash
     npm start
     ```
     The app should now be running at `http://localhost:3000`.

---

## Usage

### Adding a Task

1. Enter the task name in the input field.
2. Click the **Add Task** button or press enter.
3. The task will appear in the task list.

### Completing a Task

1. Click on the checkbox next to the task.
2. The task will be marked as completed and moved to a different section.

### Editing a Task

1. Click on the edit icon next to the task.
2. Update the task description.
3. Press save to store the changes.

### Deleting a Task

1. Click on the delete icon next to the task.
2. Confirm the deletion in the pop-up dialog.

---

## Contributing

If you'd like to contribute to this project, please fork the repository, create a new branch, and submit a pull request. All contributions are welcome!

---

## License

This project is licensed under the  UniLicense.
---
