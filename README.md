# sql_syllabus
# what is sql
SQL (Structured Query Language) is a standard language used to interact with relational databases. It lets you store, retrieve, update, and manage data efficiently.

#Main Features of SQL:

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

#Difference Between DBMS and RDBMS
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
#what are the different types of SQL commands?
DDL (Data Definition Language)
Used to create and modify the structure of database objects such as tables.

Common Commands:

CREATE – Creates a new database or table.
ALTER – Modifies an existing table.
DROP – Deletes a table or database.
TRUNCATE – Removes all rows from a table but keeps the table structure.
RENAME – Renames a table or other database object.

#create table

Creates a new database or table.

<img width="267" height="175" alt="image" src="https://github.com/user-attachments/assets/db8a6d49-9a63-4518-bf6d-a0bb122122dd" />


<img width="176" height="18" alt="image" src="https://github.com/user-attachments/assets/ab88c359-724d-4f0c-9b9b-b6664f20f94b" />



#drop table

Deletes a table or database.

<img width="167" height="32" alt="image" src="https://github.com/user-attachments/assets/f23620f5-fc0d-46d8-812c-5521d43bb394" />


#truncate
<img width="166" height="31" alt="image" src="https://github.com/user-attachments/assets/23c8d0d1-85d8-42ed-b4db-5db28eab362a" />




DML (Data Manipulation Language)

Used to insert, update, and delete data in tables.

Common Commands:

INSERT
UPDATE
DELETE

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
