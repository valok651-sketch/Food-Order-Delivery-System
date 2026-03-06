
# Food Ordering System

A full-stack food ordering web application developed using **Python Django**.  
The system allows customers to browse menu items, place orders, and track order status while restaurants manage orders efficiently.

## Features
- Customer food ordering
- Menu management
- Order tracking
- Restaurant order handling
- Delivery management

## Technologies Used
- Python
- Django
- SQLite
- HTML
- CSS

## Project Structure
Food-Ordering-System
│
├── manage.py
├── pizza/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
└── orders/
    ├── models.py
    ├── views.py
    ├── admin.py
    └── urls.py

## How to Run

1. Clone the repository

git clone https://github.com/valok651-sketch/Food-Order-Delivery-System

2. Install dependencies

pip install -r requirements.txt

3. Apply migrations

python manage.py migrate

4. Run the server

python manage.py runserver

5. Open browser

http://127.0.0.1:8000/
