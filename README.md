# 📝 To-Do List Application

A fully functional web-based to-do list app with a local Node.js/Express server backend.

## ✨ Features
- ✅ **Add/Delete/Complete tasks** - Full task management
- 🎯 **Priority levels** - High, Medium, Low priority support
- 📅 **Due dates** - Set deadlines with overdue alerts
- 🔍 **Smart filtering** - Filter by status (Active/Completed) or priority
- 📊 **Live statistics** - Track total, completed, and remaining tasks
- 💾 **Persistent storage** - Tasks saved in browser localStorage

## 🚀 Quick Start

### Prerequisites
- Node.js (v14+) installed on your system

### Installation
Dependencies are already installed. If you need to reinstall:
```bash
npm install
```

### Running the Server
Open PowerShell in the project folder and run:
```bash
npm start
```

Or use the full path if npm isn't in your PATH:
```bash
& "C:\Program Files\nodejs\npm.cmd" start
```

The server starts at: **http://localhost:3000**

### Stop the Server
Press `Ctrl+C` in your terminal

## 📖 How to Use

### Adding Tasks
1. Type your task in the input field
2. Select a priority (Low/Medium/High)
3. Optionally pick a due date
4. Click **"Add Task"** or press **Enter**

### Managing Tasks
- ✓ Check the checkbox to complete a task
- 🗑️ Click **Delete** to remove a task
- 🔄 Tasks update instantly with statistics

### Filtering Tasks
- **All** - Show all tasks
- **Active** - Show incomplete tasks only
- **Completed** - Show finished tasks
- **Priority filters** - Show tasks by priority level

### Bulk Actions
- Click **"Clear Completed Tasks"** to delete all finished tasks at once

## 📁 Project Structure
```
ToDoList/
├── server.js              # Express.js server
├── package.json           # Dependencies config
├── public/
│   ├── index.html         # Main page
│   ├── style.css          # Styling & responsiveness
│   └── script.js          # Task logic & UI
└── README.md              # This file
```

## 🛠️ Technology Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend:** Node.js + Express.js
- **Data:** Browser localStorage (client-side)
- **Port:** 3000

## 📋 Notes
- ✅ Tasks persist between sessions via localStorage
- ✅ Works offline (no database required)
- ✅ Lightweight and responsive design
- ✅ No external API calls needed

---

**Ready to stay organized?** Start adding tasks now! 🎯