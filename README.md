# Task List Project

This project is a simple **Task List App** built using **React**, allowing users to add tasks, mark them as completed using checkboxes, and delete tasks when needed.

## 🚀 Features
- **Add Tasks**: Users can enter a task and add it to the list.
- **Mark as Completed**: Each task has a checkbox to indicate completion.
- **Delete Tasks**: Remove tasks from the list with a delete button.
- **Persistent UI**: Ensures a smooth user experience with an intuitive interface.

## 📂 Project Structure
```
task-list-app/
│-- public/         # Static files (index.html, favicon, etc.)
│-- src/
│   ├── components/ # Reusable React components
│   ├── App.js      # Main app component
│   ├── Task.js     # Task component (individual task item)
│   ├── TaskList.js # List component (renders multiple tasks)
│   ├── index.js    # React entry point
│-- package.json    # Project dependencies
│-- .gitignore      # Files to ignore in Git
│-- README.md       # Project documentation
```

## 🛠 Installation & Setup
Ensure you have **Node.js** and **npm** installed.

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/task-list-app.git
   cd task-list-app
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```
   The app will run on `http://localhost:3000/`.

## 🔧 Usage
- **Add a task** by typing in the input field and pressing the add button.
- **Mark tasks as completed** by checking the checkbox.
- **Delete tasks** using the delete button.

## 📦 Dependencies
Key dependencies used in this project:
- **React** – UI library
- **useState Hook** – Manage task states
- **CSS Modules / Styled Components** – For styling the application

## 📜 License
This project is licensed under the MIT License.

---

This README provides a structured overview of the Task List App. Happy coding! 🚀
