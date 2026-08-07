# SQL_SYLLABUS

# what is DATEBASE?
A database is an organized collection of data that is stored electronically and can be easily accessed, managed, and updated.
 # You can use the database to:

Search for a student by name.
Update a student's grade.
Add a new student.
Delete a student's record.
# Why databases are used

# Databases help to:

Store large amounts of information.
Organize data efficiently.
Retrieve data quickly.
Keep data accurate and secure.
Allow multiple users to access data at the same time.

# Types of databases

# Some common types include:

Relational databases: Store data in tables with rows and columns (examples: MySQL, PostgreSQL, Oracle Database).
NoSQL databases: Store data in formats such as documents, key-value pairs, or graphs (examples: MongoDB, Apache Cassandra).

# what is SQL
SQL (Structured Query Language) is a standard language used to interact with relational databases. It lets you store, retrieve, update, and manage data efficiently.

# Main Features of SQL:

Easy to learn and use
Data querying (SELECT)
Data manipulation (INSERT, UPDATE, DELETE)
Data definition (CREATE, ALTER, DROP)
Supports relationships between tables
Ensures data integrity
Provides security and access control
Supports transaction management
Fast and efficient
Portable across different database systems

# Difference Between DBMS and RDBMS
| **DBMS (Database Management System)**                        | **RDBMS (Relational Database Management System)**                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| Stores and manages data in a database.                       | Stores and manages data in **related tables** (rows and columns).                                      |
| Relationships between data are not mandatory.                | Supports relationships using **Primary Keys** and **Foreign Keys**.                                    |
| May store data as files or simple tables.                    | Stores data only in relational tables.                                                                 |
| Data redundancy (duplicate data) is higher.                  | Reduces data redundancy through normalization.                                                         |
| May not enforce all integrity constraints.                   | Enforces data integrity using constraints like `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, and `NOT NULL`. |
| Suitable for small or simple applications.                   | Suitable for large, complex, and multi-user applications.                                              |
| Security and concurrency support are generally more limited. | Provides stronger security, transaction management, and multi-user support.                            |
| Examples: dBase, FoxPro.                                     | Examples: MySQL, PostgreSQL, Oracle Database, Microsoft SQL 
Server, SQLite. 
|
# what are the different types of SQL commands?
# SQL Command Categories
DDL (Data Definition Language): CREATE, ALTER, DROP, TRUNCATE
DML (Data Manipulation Language): INSERT, UPDATE, DELETE
DQL (Data Query Language): SELECT
DCL (Data Control Language): GRANT, REVOKE
TCL (Transaction Control Language): COMMIT, ROLLBACK, SAVEPOINT

# DDL (Data Definition Language)
Used to create and modify the structure of database objects such as tables.

# Common Commands:

CREATE – Creates a new database or table.
ALTER – Modifies an existing table.
DROP – Deletes a table or database.
TRUNCATE – Removes all rows from a table but keeps the table structure.
RENAME – Renames a table or other database object.

# CREATES TABLES

Creates a new database or table.

<img width="267" height="175" alt="image" src="https://github.com/user-attachments/assets/db8a6d49-9a63-4518-bf6d-a0bb122122dd" />

<img width="176" height="18" alt="image" src="https://github.com/user-attachments/assets/ab88c359-724d-4f0c-9b9b-b6664f20f94b" />

# DROP TABELS

Deletes a table or database.

<img width="167" height="32" alt="image" src="https://github.com/user-attachments/assets/f23620f5-fc0d-46d8-812c-5521d43bb394" />
<img width="620" height="161" alt="image" src="https://github.com/user-attachments/assets/058a1028-85c9-4c22-bf48-b93a71d690ca" />

# TRUNCATE
 Removes all rows from a table but keeps the table structure.

<img width="166" height="31" alt="image" src="https://github.com/user-attachments/assets/23c8d0d1-85d8-42ed-b4db-5db28eab362a" />

<img width="647" height="176" alt="image" src="https://github.com/user-attachments/assets/3723b97f-3170-464a-8bdb-170db5b97776" />

# DML (Data Manipulation Language)
Used to insert, update, and delete data in tables.
# Common Commands:

INSERT
UPDATE
DELETE

# INSERT
INSERT – Used to add new records (rows) into a table.

<img width="644" height="197" alt="image" src="https://github.com/user-attachments/assets/8b5d7e74-2973-44e5-9271-5874109c6821" />

# UPDATE
Used to modify existing records in a table.

<img width="676" height="288" alt="image" src="https://github.com/user-attachments/assets/25be0f4b-832b-4784-a954-e5ed61ce6e9d" />

# DELETE
Used to remove existing records from a table.

<img width="622" height="183" alt="image" src="https://github.com/user-attachments/assets/4640210c-ecd3-46db-abef-f5d09eab6c85" />

# DQL (Data Query Language);
DQL (Data Query Language) is used to retrieve data from a database.
# Common Commands:
SELECT

# SELECT

<img width="186" height="22" alt="image" src="https://github.com/user-attachments/assets/d9f23aa2-0f81-4c5d-9a31-06502b2e00d1" />


<img width="299" height="296" alt="image" src="https://github.com/user-attachments/assets/9415f96a-ba06-4286-9ff7-791db11db006" />

# DQL(DATE QUERY LANGUAGE)
The main DQL command is SELECT, which is used to retrieve data from a database.
# Explanation
SELECT – Specifies the columns to retrieve.
FROM – Specifies the table.
WHERE – Filters rows based on a condition.
GROUP BY – Groups rows with the same values.
HAVING – Filters grouped data.
ORDER BY – Sorts the result in ascending (ASC) or descending (DESC) order.
LIMIT- limit rows returned.
# SELECT
Specifies the columns to retrieve.

<img width="364" height="289" alt="image" src="https://github.com/user-attachments/assets/6c6a5303-4ff8-4b04-8555-d7307199b6c2" />

# FROM
Specifies the table

<img width="222" height="41" alt="image" src="https://github.com/user-attachments/assets/9e1af747-46fd-4db4-910a-188c075396cf" />

# WHERE
Filters rows based on a condition.

<img width="671" height="245" alt="image" src="https://github.com/user-attachments/assets/2024a087-219b-42a5-bdc0-6d0d7ad75997" />

# GROUP BY 
Groups rows with the same values

<img width="643" height="262" alt="image" src="https://github.com/user-attachments/assets/32d58499-a119-41af-bebd-7f911e0b56bc" />

# Common aggregate functions
COUNT() Counts the number of rows.
SUM() Calculates the total value.
AVG()	Calculates the average value.
MAX()	Returns the highest value.
MIN()	Returns the lowest value.

# COUNT()
Counts the number of rows

<img width="549" height="233" alt="image" src="https://github.com/user-attachments/assets/0783fa03-7136-415d-95db-e7e0b4174fd3" />

# SUM() 
Calculates the total value

<img width="580" height="207" alt="image" src="https://github.com/user-attachments/assets/7035aada-b07e-42ba-9ba5-0b00424f6891" />

# AVG()
Calculates the average value

<img width="574" height="216" alt="image" src="https://github.com/user-attachments/assets/5647e742-6051-41c5-9899-e156f9404069" />

# MAX()
Returns the highest value

<img width="572" height="213" alt="image" src="https://github.com/user-attachments/assets/72c8c7f9-6da6-43d2-86fc-1fcbb6f41927" />

# MIN()
Returns the lowest value

<img width="576" height="225" alt="image" src="https://github.com/user-attachments/assets/45f0bb11-b0bc-4b2b-b630-f2d904431e8c" />

# HAVING 
Filters grouped data.

<img width="662" height="197" alt="image" src="https://github.com/user-attachments/assets/aba058ef-f9c1-40f1-90ad-f5b119d73218" />

# ORDER BY 
Sorts the result in ascending (ASC) or descending (DESC) order.

<img width="574" height="245" alt="image" src="https://github.com/user-attachments/assets/1a10c92a-f267-46b8-874a-1daa88d5f367" />

# LIMIT
- limit rows returned.
- 
<img width="601" height="215" alt="image" src="https://github.com/user-attachments/assets/b5d0abc8-a6f3-4a65-96bc-26246e54c8d5" />

# What is SQL JOIN?
A SQL JOIN is a command used to combine data from two or more database tables based on a related column between them.
In a relational database, data is usually stored in separate tables. A JOIN helps you retrieve connected information from those tables.
# Common SQL JOIN Types

INNER JOIN _ 	Only matching rows
LEFT JOIN	 _ All left table rows + matching right rows
RIGHT JOIN _	All right table rows + matching left rows

# INNER JOIN 
Only matching rows

<img width="404" height="399" alt="image" src="https://github.com/user-attachments/assets/9a595c3f-5e42-4ab4-bdaf-efbb6b40ca6d" />

# LEFT JOIN	 
All left table rows + matching right rows

<img width="444" height="398" alt="image" src="https://github.com/user-attachments/assets/01eeb228-305b-4282-b453-06d31e4f7296" />

# RIGHT JOIN 
All right table rows + matching left rows

<img width="468" height="408" alt="image" src="https://github.com/user-attachments/assets/f9259c44-c41e-4ca5-823f-c9528e9b2312" />























                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
