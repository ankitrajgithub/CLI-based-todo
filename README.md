# 🧾 CLI Todo App  
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Commander](https://img.shields.io/badge/Commander.js-000000?style=for-the-badge&logo=npm&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A sleek and efficient **Command Line Todo Application** built with **Node.js** and the [`commander`](https://www.npmjs.com/package/commander) library.  
Easily manage your tasks — add, delete, mark done, and view todos — all from your terminal ⚡  

---

## ✨ Features

✅ Add new todos  
🗑️ Delete todos by index  
📋 View all todos with timestamps  
🏁 Mark todos as done  
💾 Persistent local storage using `todo.json`

---

## 🧩 Tech Stack

|    Technology    |           Description          |
|------------------|--------------------------------|
| **Node.js**      |      Runtime environment       |
| **Commander.js** |      CLI argument parser       |
| **fs / path**    | File system and path utilities |

---

## ⚙️ Installation

```bash
# Clone this repository
git clone https://github.com/ankitrajgithub/CLI-based-todo.git

# Install dependencies
npm install
```

---

## 🚀 Usage

Run the app using **Node.js**:

### ➕ Add a Todo
```bash
node index.js add "Buy groceries"
```
Output:
```
✅ Todo added!
```

### 📋 List Todos
```bash
node index.js list
```
Output:
```
📝 Your Todos:
0: Buy groceries ❌ Wed Nov 12 2025 00:15:42 GMT+0530 (India Standard Time)
```

### ✅ Mark Todo as Done
```bash
node index.js done 0
```
Output:
```
✅ Todo marked as done!
```

### 🗑️ Delete a Todo
```bash
node index.js delete 0
```
Output:
```
🗑️ Todo deleted!
```

---

## 📁 Project Structure

```
cli-todo-app/
├── index.js        # Main CLI logic
├── todo.json       # Local data file (auto-created)
├── package.json    # Project metadata & dependencies
└── README.md       # Documentation
```

---

## 💡 Example Workflow

```bash
node index.js add "Complete assignment"
node index.js add "Go for a run"
node index.js list
node index.js done 1
node index.js list
node index.js delete 0
```

---

## 🧠 Future Enhancements

🚀 Add task categories / tags  
🗓️ Add due dates  
🔍 Filter by completed or pending tasks  
☁️ Sync todos with cloud storage or a database  

---

## 📜 License
This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it.
