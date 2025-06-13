

# 📝 Python Checklist App

A simple and lightweight command-line checklist application built with Python. Easily create, update, and manage your tasks and checklists from your terminal.

## 🚀 Features

- Create new checklists
- Add tasks to a checklist
- Mark tasks as complete or incomplete
- Remove tasks
- Save and load checklists to/from a file (JSON)
- Lightweight and easy to use

## 📦 Requirements

- Python 3.6 or higher

You can install any optional dependencies with:

```bash
pip install -r requirements.txt

🛠️ Usage

Run the App

python checklist.py

Example Features

Create a checklist:


> New checklist created: "Daily Tasks"

Add tasks:


> Task added: "Buy groceries"
> Task added: "Walk the dog"

Mark tasks complete:


> Task marked as complete: "Buy groceries"

Save checklist to file:


> Checklist saved to daily_tasks.json

📁 Project Structure

checklist/
│
├── checklist.py         # Main application script
├── checklist_utils.py   # Helper functions and classes
├── requirements.txt     # Python dependencies (if any)
└── README.md            # Project documentation

✅ Sample Checklist Format (JSON)

{
  "title": "Daily Tasks",
  "tasks": [
    {"description": "Buy groceries", "done": true},
    {"description": "Walk the dog", "done": false}
  ]
}

