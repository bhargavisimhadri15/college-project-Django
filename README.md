# 🎓 Student Management System (Django)

A simple **Django-based Student Management System** built for college mini/major projects.  
This project performs basic **CRUD operations** and follows the **MVT (Model–View–Template)** architecture.

---

## 🚀 Features
- Add student details
- View all students
- Delete student records
- Django Admin Panel
- SQLite Database (default Django DB)

---

## 🛠️ Technologies Used
- Python 3
- Django Framework
- SQLite
- HTML
- VS Code

---

## 📂 Project Structure
college_project/
│── manage.py
│
├── college_project/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── students/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── admin.py
│ └── templates/
│ └── home.html


---

## ⚙️ Installation & Setup

### 1️⃣ Install Django
```bash
pip install django

2️⃣ Create Project
python -m django startproject college_project
cd college_project
python manage.py startapp students

3️⃣ Run Migrations
python manage.py makemigrations
python manage.py migrate

4️⃣ Run Server
python manage.py runserver


Open browser:

http://127.0.0.1:8000/

🔐 Admin Panel

Create superuser:

python manage.py createsuperuser


Admin URL:

http://127.0.0.1:8000/admin/

🧠 Architecture (MVT)

Model → Database structure

View → Business logic

Template → User interface

🎓 College Viva Points

Django uses MVT architecture

SQLite is used as backend database

CRUD operations implemented

Admin panel for database management

📌 Future Enhancements

Update student details

Search functionality

Login system

CSS & Bootstrap UI

👨‍💻 Developed By

Bhargavi Simhadri
College Project – Django
