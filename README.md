# adhd-scheduler
Tool for task management.
    Add and complete tasks, 
    prioritize tasks based on time constraints,
    prioritize tasks based on difficulty level
    maintain a healthy workflow while prioritizing mental load,
    offline usability with 0 compromises

In future releases, AI integration will be added, running locally on a device's NPU or GPU.

The job of the AI is to allow the app to learn how the user handles tasks and to monitor the users mental state through changes in task completion. This, in turn, allows the
application to adjust to the user and ensure a healthy workflow while preventing burnout.


# tech stack
Language: Python

UI Framework: Qt (using PySide for Python bindings)

AI Framework: ONNX Runtime (for future AI integration)

Database: SQLite (for storing tasks, schedules, and user preferences)

Build Tools: PyInstaller or PyOxidizer (for packaging into a standalone executable, if needed)
