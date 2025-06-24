## django-recipe-api
This project is a fully-featured Recipe Management REST API built using Django and Django REST Framework (DRF). It allows authenticated users to create, retrieve, update, and manage recipes, along with related tags, ingredients, and recipe images. It follows best practices for modular Django project structure, test coverage, and image handling — suitable for real-world backend development.

# Features
1. Token-based authentication using DRF’s TokenAuthentication

2. Recipe CRUD operations with support for:

3. Tags (e.g., Dinner, Breakfast)

4. Ingredients (e.g., Garlic, Tomato)

5. Image upload functionality for each recipe

6. Fully tested using unittest.TestCase and DRF’s APIClient

7. Swagger/OpenAPI integration using drf-spectacular

8. Media file support for image uploads (non-Docker setup)

9. Built-in validation and relational integrity checks


# Tech Stack
1. Backend: Django 5.2.1, Django REST Framework 3.16

2. Database: SQLite (or switchable to PostgreSQL/MongoDB)

3. API Documentation: drf-spectacular

4. Testing: Django TestCase, DRF APIClient

5. Media Handling: Pillow (image processing), ImageField storage
