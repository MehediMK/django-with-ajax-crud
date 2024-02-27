# Django TodoList with AJAX

This project is a simple TodoList application built using Django framework with AJAX for smooth interaction between the client and server.

## Prerequisites

- Python 3.x +
- pip
- Django
- Jquery

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/MehediMK/django-with-ajax-crud.git
```

### 2. Create and Activate Virtual Environment

```bash
cd django-with-ajax-crud
python3 -m venv venv
```

For Windows:

```bash
cd django-todolist-ajax
python -m venv venv
```

Activate the virtual environment:

```bash
source venv/bin/activate
```

For Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Optional)

You can create a superuser to access the Django admin panel.

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

The application will be available at `http://localhost:8000`.

## Usage

- Visit `http://localhost:8000` in your browser to access the TodoList application.
- You can add new tasks, mark tasks as completed, and delete tasks.
- AJAX is used for seamless interaction without page reloads.

## Project Structure

```
django-with-ajax-crud/
├── todo_app/                  # Django app for the TodoList
│   ├── migrations/           # Database migrations
│   ├── static/               # Static files (JavaScript, CSS)
│   ├── templates/            # HTML templates
│   ├── admin.py              # Django admin configurations
│   ├── models.py             # Database models
│   ├── urls.py               # URL patterns
│   └── views.py              # View functions
├── todo_project/    # Django project settings
│   ├── settings.py           # Project settings
│   └── urls.py               # Project-level URL patterns
├── static/                   # Static files (JavaScript, CSS)
├── templates/                # HTML templates
├── .gitignore                # Specifies intentionally untracked files to ignore
├── manage.py                 # Django's command-line utility for administrative tasks
├── config.py                 # Enter you config here
└── README.md                 # Project README file
```

## Technologies Used

- Django
- AJAX
- HTML
- CSS
- jquery

## Contributors

- [Mehedi Khan](https://github.com/MehediMK)

Feel free to contribute to this project by forking and submitting a pull request. Any feedback or suggestions are also appreciated!
