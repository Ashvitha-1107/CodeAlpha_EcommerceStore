# CodeAlpha_EcommerceStore

## Simple E-Commerce Store using Django

### Project Description
A simple E-Commerce website developed using Django, HTML, CSS, and SQLite. Users can browse products, view product details, register/login, add products to a shopping cart, and place orders. The admin panel allows management of products and orders.

---

## Features

- Product Listing Page
- Product Details Page
- Shopping Cart
- User Registration
- User Login
- Order Processing (Checkout)
- Admin Panel
- Database Integration using SQLite

---

## Technologies Used

- Python
- Django
- HTML5
- CSS3
- SQLite3

---

## Project Structure

```
CodeAlpha_EcommerceStore/
│
├── ecommerce/
│   ├── settings.py
│   ├── urls.py
│
├── store/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   ├── home.html
│   │   ├── product_detail.html
│   │   ├── cart.html
│   │   ├── register.html
│   │   └── order_success.html
│   │
│   └── static/
│       └── css/
│           └── style.css
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone <your-repository-url>
cd CodeAlpha_EcommerceStore
```

### Install Django

```bash
pip install django
```

### Apply Migrations

```bash
python manage.py migrate
```

### Run the Server

```bash
python manage.py runserver
```

### Open in Browser

```
http://127.0.0.1:8000/
```

---

## Admin Login

```text
URL: http://127.0.0.1:8000/admin
```

Create a superuser:

```bash
python manage.py createsuperuser
```

---

## Functionalities Implemented

### Product Management
- View products
- Product details page

### Shopping Cart
- Add products to cart
- View cart items

### User Authentication
- User registration
- User login

### Order Processing
- Checkout functionality
- Order creation
- Order storage in database

### Admin Panel
- Manage products
- Manage orders
- Manage users

---

## Internship Task

**CodeAlpha Internship**

**Task 1: Simple E-Commerce Store**

### Requirements Covered

- Product Listings ✅
- Product Details Page ✅
- Shopping Cart ✅
- User Registration/Login ✅
- Order Processing ✅
- Database Storage ✅

---

## Author

**Ashvitha M C P**

CodeAlpha Internship Program