# Flask Notes App

A simple web application for creating and managing notes built with Flask and SQLite.

## Features
- ✅ Create new notes with title and content
- ✏️ Edit existing notes
- 🗑️ Delete notes
- 📋 View all notes in a clean interface
- 💾 SQLite database for data persistence
- 🎨 Bootstrap UI with gradient background

## Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open your browser and go to:
```
http://127.0.0.1:5000
```

## Technologies Used
- Flask (Python web framework)
- SQLAlchemy (Database ORM)
- SQLite (Database)
- Bootstrap 5 (Frontend styling)
- HTML/CSS

## Project Structure
```
flask-notes-app/
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── templates/          # HTML templates
│   ├── base.html      # Base template
│   ├── index.html     # Home page
│   ├── add.html       # Add note page
│   └── edit.html      # Edit note page
└── notes.db           # SQLite database (created automatically)
```

## CRUD Operations
- **Create**: Add new notes via `/add` route
- **Read**: View all notes on home page
- **Update**: Edit notes via `/edit/<id>` route
- **Delete**: Remove notes via `/delete/<id>` route
