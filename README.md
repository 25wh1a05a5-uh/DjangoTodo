# Django TODO Application

A simple and user-friendly TODO application developed using Python and Django. This application allows users to manage their daily tasks by adding, viewing, completing, undoing, and deleting tasks.

## Features

- Add new tasks.
- View all tasks.
- Mark tasks as completed.
- Undo completed tasks.
- Delete tasks.
- Store tasks using SQLite database.
- Data persistence after refreshing the browser.

## Technologies Used

- **Frontend:** HTML
- **Backend:** Python, Django
- **Database:** SQLite
- **Version Control:** Git and GitHub

## Project Structure

```text
DjangoTodo/
│
├── todoproject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── tasks/
│   ├── migrations/
│   ├── templates/
│   │   └── tasks/
│   │       └── home.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── venv/
├── db.sqlite3
├── manage.py
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/25wh1a05a5-uh/DjangoTodo.git
```

### 2. Navigate to the project directory

```bash
cd DjangoTodo
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

For Windows Command Prompt:

```cmd
venv\Scripts\activate.bat
```

### 5. Install Django

```bash
python -m pip install django
```

### 6. Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Run the development server

```bash
python manage.py runserver
```

### 8. Open the application

Visit the following URL in your browser:

http://127.0.0.1:8000/

## Application Usage

1. Enter a task in the input field.
2. Click **Add Task** to create a task.
3. View all added tasks on the home page.
4. Click **Complete/Undo** to change the task status.
5. Click **Delete** to remove a task.

## Database

The application uses SQLite to store task information.

The Task model contains:

- `title`: Stores the task description.
- `completed`: Stores the completion status (True/False).

## Future Enhancements

- Add user registration and login.
- Add task deadlines and priorities.
- Improve the interface using CSS and Bootstrap.
- Add task search and filtering.

## Author

**25wh1a05a5-uh**

## License

This project is developed for educational purposes.
