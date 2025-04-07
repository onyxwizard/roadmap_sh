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
git clone https://github.com/onyxwizard/roadmap_sh.git

cd roadmap-sh//python_projects/task_tracker
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
task-tracker-cli/
│
├── task_cli/                    # Contains the Python project files
│   ├── task_cli.py              # Main CLI entry point
│   ├── tasks.json               # JSON file for task storage
│   │
│   ├── models/                  # Core entity classes
│   │   └── task.py              # Task class
│   │
│   ├── services/                # Business logic
│   │   └── task_service.py      # Task management logic
│   │
│   ├── utils/                   # Utilities
│   │   ├── file_handler.py      # File system operations
│   │   └── cli_parser.py        # CLI argument parsing
│   │
│   └── README.md                # Documentation for the project
│
└── README.md                    # Root-level documentation
```