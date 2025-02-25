project_sql
SQL PROJECT This project demonstrates how to manage and manipulate data using SQL and SQLite within a Python environment. It covers essential CRUD (Create, Read, Update, Delete) operations as well as more advanced queries such as joins and aggregate functions.

- Project Structure Tables: alunos (Students): Contains student data including id, name, age, and course. clientes (Clients): Stores client information such as id, name, age, and balance. compras (Purchases): Records purchase details with fields for id, client_id (foreign key referencing clientes), product, and value.
- Key Functionalities: Table Creation & Data Insertion: Creating tables and inserting records using SQL commands.
- Basic Queries: Retrieving records using SELECT statements with conditions.
- Aggregate Functions: Calculating metrics such as average balance, maximum balance, and counts using functions like AVG(), MAX(), and COUNT().
- Data Manipulation: Updating and deleting records based on specific conditions.
- Joins: Combining data from multiple tables to display comprehensive information (e.g., linking clients to their purchases).

The code is implemented using Python’s sqlite3 module and is designed for educational purposes, illustrating practical examples of SQL operations. This project is ideal for those learning SQL and database management as it provides hands-on experience with real data manipulation tasks.
