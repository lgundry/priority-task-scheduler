# adhd-scheduler
AI assistant for task management. 
    Add and complete tasks, 
    prioritize tasks based on time constraints,
    prioritize tasks based on difficulty level
    maintain a healthy workflow while prioritizing mental load



# tech stack
Language: Python

UI Framework: Qt (using PySide for Python bindings)

AI Framework: ONNX Runtime (for future AI integration)

Database: SQLite (for storing tasks, schedules, and user preferences)

Build Tools: PyInstaller or PyOxidizer (for packaging into a standalone executable, if needed)

# project structure (subject to change)
/task_manager
│── /src                     # Main source code
│   ├── main.py              # Entry point of the application
│   ├── ui_main.py           # Main Qt UI logic
│   ├── database.py          # Handles SQLite operations
│   ├── scheduler.py         # Task scheduling logic
│   ├── burnout_checker.py   # Burnout detection logic
│   ├── ai_module.py         # Placeholder for future AI logic
│   ├── config.py            # App-wide settings
│── /assets                  # Icons, images, etc.
│── /tests                   # Unit tests
│── requirements.txt         # Python dependencies
│── README.md                # Project documentation
│── setup.py                 # Packaging and installation script