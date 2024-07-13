#### Pravin Patrike (25PGAI0008)
### CRUD Operations with MySQL and FastAPI

### step 1.
#### Setting up MySQL server

1. Created a local Instance in MySQL workbench and created a databse school
2. Created a Table students with columns id, name , age , grade.

![alt text](image.png)

### step 2.
####  Implement CRUD Wrapper Functions
1. Install mysql-connector-python:
``` pip install mysql-connector-python ```
2. created a database.py module

Create a Python module database.py to implement the database connection and
CRUD operations.

### Step 3
#### Develop RESTful APIs with FastAPI
1. Install FastAPI and Uvicorn:
    ``` pip install fastapi uvicorn ```
2. Created FastAPI Application: Created a file named main.py

3. Run the FastAPI Application:
uvicorn main:app --reload
