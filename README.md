# Task Manager App

A simple web application for managing daily tasks with CRUD (Create, Read, Update, Delete) functionality.

## Features
- Add new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Mark tasks as complete/incomplete

## Tech Stack
- Flask (Python web framework)
- SQLite (Database)
- SQLAlchemy (ORM)
- HTML/CSS

## Setup Instructions

1. Clone the repository:
```bash
git clone <your-repository-url>
cd task-manager-app
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Project Structure
```
task-manager-app/
├── app.py              # Main application file
├── models.py           # Database models
├── static/            # Static files (CSS, JS)
├── templates/         # HTML templates
├── requirements.txt   # Project dependencies
└── README.md         # Project documentation
```