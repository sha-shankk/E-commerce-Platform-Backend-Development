# E-commerce Platform Backend

This project is a backend implementation for an e-commerce platform using Django and Django REST framework. It includes functionalities for managing products, user authentication, and order processing.

## Features

- Product management (CRUD operations)
- User registration and authentication
- Order management (place, view, and manage orders)
- RESTful API endpoints

## Tech Stack

- Django
- Django REST framework
- SQLite (default, can be configured for other databases)
- Docker (optional for containerization)

## Installation

1. Clone the repository:

   git clone https://github.com/sha-shankk/E-commerce-Platform-Backend-Development.git
   cd ecommerce_platform

2. Create a virtual environment and activate it:

  python3 -m venv venv
  source venv/bin/activate

3. Install the dependencies:

  pip install -r requirements.txt

4.Apply the database migrations:

  python manage.py migrate

5.Create a superuser for accessing the Django admin:

  python manage.py createsuperuser

6. Run the development server:

    python manage.py runserver

    Access the API at http://localhost:8000/api/ and the admin panel at http://localhost:8000/admin/.

API Endpoints
Products

    GET /api/products/ - List all products
    POST /api/products/ - Create a new product
    GET /api/products/<id>/ - Retrieve a product
    PUT /api/products/<id>/ - Update a product
    DELETE /api/products/<id>/ - Delete a product

Users

    GET /api/users/ - List all users
    POST /api/users/ - Create a new user
    `GET /api/users/<id>/
