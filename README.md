# 📝 Django Blog Website

This is a beginner-friendly Django blog website project developed to understand the fundamental workings of Django's MVC (Model-View-Template) architecture. The project allows users (admin only, for now) to create and manage blog posts.

---

## 🔧 Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (basic templating)
- **Database**: SQLite (default)
- **Others**: Django Admin, Git/GitHub

---

## 🚀 Features

- Home page displaying all blog posts.
- Detail page for each blog post.
- Admin panel for creating/editing/deleting blog posts.
- Simple, clean, responsive UI using Django templates.

---

## 🧩 Project Structure
blog_project/ ├── blog/ # Main app │ ├── models.py # BlogPost model │ ├── views.py # Logic to display posts │ ├── urls.py # URL routing for blog │ └── templates/ # HTML templates ├── blog_project/ │ └── settings.py # Project configuration ├── db.sqlite3 # Default database └── manage.py


---

## 📦 How to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/django-blog.git
cd django-blog

2.Set up a virtual environment and install Django:
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install django

3.Run migrations and start the server:
python manage.py migrate
python manage.py runserver

4.Access the app at http://127.0.0.1:8000/.

---

🧠 What I Learned
Django project and app setup

Django models, views, and templates (MVT)

URL routing and database interaction

Admin interface and CRUD operations
