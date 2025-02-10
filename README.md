# BlogSite - Django Blog Post Project

## 📌 Introduction
BlogSite is a full-fledged blogging platform built using Django. It allows users to create, edit, delete, and manage blog posts while offering user authentication, commenting, and role-based access control. The project is designed for bloggers, writers, and readers who want an engaging and interactive platform to share their thoughts.

## 🚀 Features
- **User Authentication** (Sign Up, Login, Logout, Password Reset)
- **Role-Based Access Control** (Admin, Author, Viewer)
- **Create, Edit & Delete Blog Posts**
- **User-Friendly Dashboard for Authors**
- **Commenting System**
- **Responsive UI with Tailwind CSS**

## 🛠️ Technologies Used
- **Backend:** Django, Django REST Framework
- **Frontend:** HTML, Tailwind CSS
- **Database:** SQLite (can be switched to PostgreSQL)
- **Authentication:** Django's built-in auth system

## ⚡ Installation & Setup
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/abhishekmane1911/BlogSite.git
 cd BlogSite
```

### 2️⃣ Create a Virtual Environment
```sh
 python3 -m venv venv
 source venv/bin/activate  # Mac/Linux
 venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies
```sh
 pip install -r requirements.txt
```

### 4️⃣ Apply Migrations & Run Server
```sh
 python manage.py makemigrations
 python manage.py migrate
 python manage.py runserver
```
Access the app at **http://127.0.0.1:8000/**

## 👤 User Roles
- **Admin:** Full control over posts, users, and comments
- **Author:** Can create, edit, and delete their own posts
- **Viewer:** Can read posts and leave comments


## 📧 Contact
For queries, reach out to **Abhishek Mane** at [GitHub](https://github.com/abhishekmane1911).

---
**Happy Blogging! 📝🚀**

