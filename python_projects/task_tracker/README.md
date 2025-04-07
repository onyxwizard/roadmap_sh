## 🐍 Python Projects 
### 1. Task Tracker CLI  📋 

A simple Command-Line Interface (CLI)  application to manage tasks efficiently. Built using Python and following Object-Oriented Programming (OOP) principles. 

#### Features ✨ 

```bash
* Add, update, and delete tasks.
* Mark tasks as "in-progress" or "done".
* List tasks by status (todo, in-progress, done).
     
```   

### Installation 💻 
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/roadmap-sh.git

cd roadmap-sh/python-projects/task-tracker-cli
```

2. Run the CLI application:

```bash
python task_cli.py <command> [arguments]
```

### Usage 🛠️ 

* Add a task:
```bash
python task_cli.py add "Buy groceries"
```
* Update a task:
```bash
python task_cli.py update 1 "Buy groceries and cook dinner"
```
* Delete a task:
```bash
python task_cli.py delete 1
```

* List tasks:
```bash
python task_cli.py list
```


## Folder Structure 🗂️
```bash
task_cli/: Contains the Python project files.
task_cli.py: Main CLI entry point.
tasks.json: Stores tasks in JSON format.
models/: Core entity classes (e.g., Task).
services/: Business logic (e.g., task management).
utils/: Utility functions (e.g., file handling, CLI parsing

```