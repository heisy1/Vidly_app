# Vidly – Movie Management App

Vidly is a simple web application built with **Django** for managing movie data. It uses **SQLite** as its database and provides an API for accessing movie information.

## Features

- **Movie Management:** Store and manage movie-related data.
- **REST API:** Access movie data through API endpoints.
- **Admin Panel:** Use Django's built-in administration interface to manage and edit data.
- **SQLite Database:** Store application data in a lightweight relational database.

## Technologies Used

- Python
- Django
- SQLite
- Django REST API / Tastypie

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/heisy1/Vidly_app.git
cd Vidly_app
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Apply database migrations

```bash
python manage.py migrate
```

### 4. Start the development server

```bash
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.

## Admin Panel

To access the Django admin panel, create a superuser:

```bash
python manage.py createsuperuser
```

Then visit `http://127.0.0.1:8000/admin/` and log in with your credentials.

## License

This project was created for learning and practicing Django web development.
