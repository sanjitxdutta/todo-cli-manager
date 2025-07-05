# 📝 Todo CLI Manager

A simple and powerful command-line task manager built with Node.js using the `commander` library. Manage your daily tasks — add, delete, update, and mark them as done — all from your terminal!

---

## 📦 Features

- ➕ Add new tasks  
- ❌ Delete existing tasks  
- ✏️ Update task names  
- ✅ Update completion status  
- 📃 List all tasks with their status  

---

## 🚀 Installation

```bash
git clone https://github.com/sanjitxdutta/todo-cli-manager.git
cd todo-cli-manager
npm install
```

---

## 🔧 Usage

You can run the CLI using:

```bash
node index.js <command>
```

### Available Commands

#### Add a task

```bash
node index.js add-todo "Buy groceries"
```

#### Delete a task

```bash
node index.js delete-todo "Buy groceries"
```

#### Update a task

```bash
node index.js update-todo "Buy groceries" "Buy fruits"
```

#### Update task status

```bash
node index.js update-status "Buy fruits" true
```

#### List all tasks

```bash
node index.js list-todos
```

---

## 📂 Project Structure

```
todo-cli-manager/
│
├── index.js             # Main CLI logic
├── task.json            # JSON file to store your tasks
├── package.json         # Project metadata and dependencies
└── package-lock.json    # Dependency lock file
```

---

## 📽️ Demo


https://github.com/user-attachments/assets/96b737e7-ede6-4cb3-a1a5-44003b3bef61


---

## 🛠️ Built With

- [Node.js](https://nodejs.org/)
- [Commander.js](https://www.npmjs.com/package/commander)
- [File System (fs)](https://nodejs.org/api/fs.html)

---

## 📄 License

This project is licensed under the ISC License.

---

## 🙋‍♂️ Author

**Sanjit Dutta**  
[GitHub Profile](https://github.com/sanjitxdutta)
