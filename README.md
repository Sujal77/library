This project is a simple REST API for managing books in a library.
It is built using Django and Django REST Framework (DRF).
The API supports basic CRUD operations along with filtering and pagination.

Pagination is enabled using Django REST Framework settings
Example Request (POST)
{
"title": "Atomic Habits",
"author": "James Clear",
"published_date": "2018-10-16",
"isbn": "1234567890123",
"available_copies": 5
}
API Access (Local)
http://127.0.0.1:8000/books/⁠
Author
Your Name
