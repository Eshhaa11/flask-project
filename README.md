# 📚 Library RESTful API (Flask + SQLite)

This is a simple RESTful API for managing a library system using **Flask**, **Flask-RESTful**, and **SQLite**. It supports full **CRUD** operations for books and authors.

---

## 🚀 Features

- ✅ Create, Read, Update, Delete books
- ✅ Create, Read, Update, Delete authors
- ✅ Input validation and error handling
- ✅ SQLite database using SQLAlchemy ORM
- ✅ Modular code structure
- ✅ Flask-RESTful API architecture

---

## 🏗️ Project Structure

Library-API/
│
├── app.py # Main app runner
├── db.py # Database setup (SQLAlchemy instance)
│
├── models/
│ ├── book.py # BookModel definition
│ └── author.py # AuthorModel definition
│
├── resources/
│ ├── book.py # Book API endpoints
│ └── author.py # Author API endpoints
│
└── README.md # Project documentation


---

## 📦 Requirements

Install Python packages with pip:

```bash
pip install Flask Flask-RESTful Flask-SQLAlchemy

