# Flask To-Do App

This is a simple web-based CRUD To-Do application built using the Flask framework. It allows users to manage their tasks through a user-friendly interface.

## Features

- Add new tasks
- View existing tasks
- Update task details
- Delete tasks

## Prerequisites

- Python 3.x
- Flask

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/joaorihan/flask-todo-app.git
   cd flask-todo-app
   ```


2. **Create and activate a virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```


3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```


## Usage

1. **Set environment variables:**

   ```bash
   export FLASK_APP=app.py
   export FLASK_ENV=development
   ```


   *On Windows:*

   ```bash
   set FLASK_APP=app.py
   set FLASK_ENV=development
   ```


2. **Initialize the database:**

   ```bash
   flask init-db
   ```


3. **Run the application:**

   ```bash
   flask run
   ```


   The application will be accessible at `http://127.0.0.1:5000/`.

## Project Structure


```
flask-todo-app/
│
├── app.py
├── requirements.txt
├── instance/
│   └── todo.sqlite
├── static/
│   └── css/
│       └── style.css
└── templates/
    ├── base.html
    ├── index.html
    └── update.html
```


- **`app.py`**: The main application file containing routes and application logic.
- **`requirements.txt`**: File listing the Python dependencies.
- **`instance/todo.sqlite`**: SQLite database file.
- **`static/css/style.css`**: Stylesheet for the application.
- **`templates/`**: Directory containing HTML templates.

This was based on the [freeCodeCamp's flask tutorial](https://www.youtube.com/watch?v=Z1RJmh_OqeA&t=2464s&pp=ugMICgJwdBABGAHKBQ5mbGFzayB0dXRvcmlhbA%3D%3D)
