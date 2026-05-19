# 🛍️ Mini Shop

A simple e-commerce web application built with Django.

## 📋 Features

- Browse products on the home page
- Click on any product to view its details
- Clean and responsive grid layout
- Admin panel to manage products

## 🛠️ Technologies Used

- Python 3.12
- Django 6.0
- HTML & CSS
- SQLite

## 🚀 How to Run

1. Clone the project
2. Install Django:
   pip install django
3. Run migrations:
   python manage.py migrate
4. Create admin user:
   python manage.py createsuperuser
5. Start the server:
   python manage.py runserver
6. Open browser at:
   http://127.0.0.1:8000

## 📁 Project Structure

webproject/
├── shop/
│   ├── templates/shop/
│   │   ├── home.html
│   │   └── product_detail.html
│   ├── static/shop/
│   │   └── style.css
│   ├── models.py
│   ├── views.py
│   └── urls.py
└── webproject/
    ├── settings.py
    └── urls.py

