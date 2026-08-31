# To-Do List Application

A fully functional web-based to-do list application with a local Node.js server.

## Features
- ✅ Add/Delete/Complete tasks
- 🎯 Priority levels (High, Medium, Low)
- 📅 Due dates with overdue alerts
- 🔍 Smart filtering by status and priority
- 📊 Task statistics
- 💾 Persistent storage (localStorage)

## Prerequisites
- Node.js (v14 or higher)
- npm (comes with Node.js)

## Installation & Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the server:**
   ```bash
   npm start
   ```

3. **Open your browser:**
   - Navigate to `http://localhost:3000`
   - The application will load and you can start creating tasks

## Usage

1. **Add a Task:**
   - Type your task in the input field
   - Select a priority level (Low, Medium, High)
   - Optionally select a due date
   - Click "Add Task" or press Enter

2. **Manage Tasks:**
   - Check the checkbox to mark tasks as complete
   - Click "Delete" to remove a task
   - Use the filter buttons to view specific tasks

3. **Filter Options:**
   - **All**: Show all tasks
   - **Active**: Show incomplete tasks
   - **Completed**: Show completed tasks
   - **Priority Filters**: Show tasks by priority level

4. **Clear Completed:**
   - Click "Clear Completed Tasks" to delete all finished tasks at once

## Files Structure
```
ToDoList/
├── server.js           # Express server
├── package.json        # Node.js dependencies
├── public/
│   ├── index.html      # Main HTML file
│   ├── style.css       # Stylesheet
│   └── script.js       # Frontend JavaScript
└── README.md           # This file
```

## How to Stop the Server
Press `Ctrl+C` in your terminal to stop the server.

## Technology Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend:** Node.js with Express.js
- **Storage:** Browser localStorage (client-side)
- **Port:** 3000 (default)

## Notes
- All tasks are stored in your browser's localStorage, so they persist between sessions
- The server is lightweight and perfect for development
- No database is required

Enjoy organizing your tasks! 📝