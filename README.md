# User CRUD API with Django Rest Framework

A simple REST API for **user management** built with **Django Rest Framework (DRF)**. This project demonstrates how to implement CRUD (Create, Read, Update, Delete) operations for users using DRF's serializers, viewsets, and routers.

## 🚀 Features

* Create new users
* List all users
* Retrieve a single user by ID
* Update user details
* Delete users
* RESTful endpoints following DRF conventions

## 🛠️ Tech Stack

* Python 3
* Django
* Django Rest Framework
* SQLite (default database)

## 📂 Project Structure

```
DjangoRest - users/
├── users/        # User CRUD app
├── config/      # Django project configuration
├── manage.py     # Django CLI tool
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/JosepRivera/djangorest-users.git
cd drf-user-crud
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

API will be available at: `http://127.0.0.1:8000/api/users/`

## 📌 API Endpoints

* `GET /api/users/` → List all users
* `POST /api/users/` → Create new user
* `GET /api/users/{id}/` → Retrieve user by ID
* `PUT /api/users/{id}/` → Update user
* `DELETE /api/users/{id}/` → Delete user

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork this project and submit a pull request.
