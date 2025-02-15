# 📌 To-Do List Task Manager

A simple task manager to add, delete, and prioritize tasks efficiently with a user-friendly interface and responsive design.

## 🚀 Features

✅ **Manage Tasks** – Add, edit, and delete tasks easily.\
✅ **Prioritization** – Set task priorities for better productivity.\
✅ **Progress Tracking** – Monitor completed and pending tasks.\
✅ **User Authentication** – Secure user login and task management (if applicable).\
✅ **Dark Mode Support** – Enhances user experience with light/dark themes.

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (if applicable)
- **Authentication**: JWT (if applicable)

## 📷 Screenshots

*(Include some images of the UI here for better presentation.)*

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/todo-list.git
   cd todo-list
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
4. Open in browser:
   ```
   http://localhost:3000
   ```

## 🧑‍💻 Usage

- **Adding a Task**:

  ```javascript
  fetch('/add-task', {
    method: 'POST',
    headers: {'Content-Type': 'application/json'},
    body: JSON.stringify({ task: 'New Task', priority: 'High' })
  })
  .then(response => response.json())
  .then(data => console.log(data));
  ```

- **Deleting a Task**:

  ```javascript
  fetch('/delete-task', {
    method: 'DELETE',
    headers: {'Content-Type': 'application/json'},
    body: JSON.stringify({ taskId: '12345' })
  })
  .then(response => response.json())
  .then(data => console.log(data));
  ```

## 📌 Future Enhancements

- Add **reminders and notifications**.
- Implement **drag-and-drop task reordering**.
- Introduce **collaborative task sharing**.

##

## 📜 License

This project is open-source under the **MIT License**.



