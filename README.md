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

 # what is SQL logical operators?
 SQL logical operators are keywords used to combine, modify, or reverse conditions in an SQL query. They are mainly used with the WHERE clause to filter data.

# Main SQL Logical Operators
AND – Both conditions must be true.
OR – At least one condition must be true.
NOT – Reverses a condition.

# AND 
Both conditions must be true.

<img width="507" height="275" alt="image" src="https://github.com/user-attachments/assets/57eb9908-016f-4292-8a15-1ed1285dba24" />

# OR 
At least one condition must be true.

<img width="516" height="269" alt="image" src="https://github.com/user-attachments/assets/e4808244-94fe-41dc-8c27-66f5c22c6f2e" />

# NOT 
Reverses a condition.

<img width="424" height="242" alt="image" src="https://github.com/user-attachments/assets/a0e8bd40-62ed-4664-ab68-7fa00b8bcacd" />

# what is SQL special operators
SQL special operators are operators used to perform specific types of comparisons or searches in SQL. They make it easier to filter data.

# Operator	Purpose
BETWEEN	_ Checks a range
IN	_ Checks values in a list
LIKE _	Searches for a pattern
IS NULL _	Checks for NULL values
EXISTS _	Checks whether records exist

# BETWEEN	
Checks a range

<img width="492" height="247" alt="image" src="https://github.com/user-attachments/assets/5e7d0b0d-738c-44e2-afbc-5513b3fdac0c" />

# IN	
Checks values in a list

<img width="543" height="249" alt="image" src="https://github.com/user-attachments/assets/1145d196-ece3-49e3-a83c-ecf8c72b5862" />

# LIKE 
Searches for a pattern

<img width="445" height="240" alt="image" src="https://github.com/user-attachments/assets/5ab2c637-2f2c-4aa9-a678-f9aecd66f901" />

# IS NULL 
Checks for NULL values

<img width="545" height="106" alt="image" src="https://github.com/user-attachments/assets/5078b2f3-eac3-4fc9-a49c-60d783928093" />

# EXISTS 
Checks whether records exist



# what is SQL comparison operators
SQL comparison operators are operators used to compare two values or expressions. They are mainly used in the WHERE clause to filter records.

# Common SQL Comparison Operators
=	   Equal to	  
<> or !=	 Not equal to	 
>	    Greater than	marks 
<	    Less than	marks 
>=   	Greater than or equal to	marks 
<=	   Less than or equal to

# =	  
Equal to	

<img width="437" height="154" alt="image" src="https://github.com/user-attachments/assets/ae512531-7f86-421a-a56c-d73f42469df0" />

# <> or !=	
Not equal to	 

<img width="425" height="247" alt="image" src="https://github.com/user-attachments/assets/a9d8298e-e2ac-418b-988e-3103500d1157" />

<img width="425" height="252" alt="image" src="https://github.com/user-attachments/assets/4168579d-0375-42b2-b1db-e3798da6ff7d" />

# >	 
Greater than	

<img width="440" height="236" alt="image" src="https://github.com/user-attachments/assets/d9ce7882-1527-4feb-9ec7-01051012b12b" />

# <	  
Less than	

<img width="421" height="237" alt="image" src="https://github.com/user-attachments/assets/ed82d7ad-6f41-4880-b8fc-867a9712d72e" />

# >=
Greater than or equal to	

<img width="438" height="244" alt="image" src="https://github.com/user-attachments/assets/e3f9cd0e-4b2b-474f-8aa5-25ebe86c2360" />

# <=
less than or equal to

<img width="417" height="246" alt="image" src="https://github.com/user-attachments/assets/ecd6ef00-dcd4-44cf-bf11-f83d61dc4d0e" />

# what is SQL string function
SQL string functions are built-in functions used to work with text (string) data in a database. They can be used to change, search, combine, or find information in strings.

# Main Types of SQL String Functions
UPPER() – converts text to uppercase.
LOWER() – converts text to lowercase.
LENGTH() – finds the number of characters.
CONCAT() – joins two or more strings.
SUBSTRING() – extracts part of a string.
TRIM() – removes unwanted spaces from the beginning and end.
REPLACE() – replaces one part of a string with another.

# CONCAT() 
joins two or more strings.

<img width="395" height="131" alt="image" src="https://github.com/user-attachments/assets/14d29f3a-c6e1-40ab-8c88-135fde581ad2" />

# LENGTH() 
finds the number of characters.

<img width="341" height="129" alt="image" src="https://github.com/user-attachments/assets/b91b2b99-de51-44da-9bb9-05f4d4ed6f8e" />

# UPPER() 
converts text to uppercase.

<img width="304" height="137" alt="image" src="https://github.com/user-attachments/assets/696d9c00-b7b1-45ac-ba4a-ddc050696838" />

# LOWER() 
converts text to lowercase.

<img width="295" height="135" alt="image" src="https://github.com/user-attachments/assets/894c1415-53a8-4458-891b-1bdd475d2003" />

# SUBSTRING() 
extracts part of a string.

<img width="396" height="159" alt="image" src="https://github.com/user-attachments/assets/79ccd812-4af0-4d43-b314-d51316253178" />

# TRIM() 
removes unwanted spaces from the beginning and end.

<img width="348" height="153" alt="image" src="https://github.com/user-attachments/assets/7e23de2e-3362-434a-97b5-941efbe8004a" />

# REPLACE() 
replaces one part of a string with another.

<img width="492" height="167" alt="image" src="https://github.com/user-attachments/assets/6e04e1c1-59ce-4a02-986f-50b4c05aa713" />

# what is SQL Arithmetic operations?
SQL arithmetic operations are mathematical calculations performed on numeric values in SQL queries. They are commonly used to calculate totals, differences, percentages, salaries, prices, etc.

# Types of Arithmetic Operations in SQL
+     	Addition	
-      Subtraction		
*      Multiplication	
/	      Division	
%	      Modulus (remainder)

# +     	Addition	

<img width="583" height="253" alt="image" src="https://github.com/user-attachments/assets/4bfcff47-30ee-452c-8fa8-e8c09f188910" />

# -      Subtraction	

<img width="601" height="237" alt="image" src="https://github.com/user-attachments/assets/ea2616a3-eb60-45ac-bac3-f7967c970df7" />

# *      Multiplication	

<img width="593" height="258" alt="image" src="https://github.com/user-attachments/assets/1a4f36e2-270f-480c-8be3-363e63d7b951" />

# /	      Division	

<img width="589" height="251" alt="image" src="https://github.com/user-attachments/assets/1ce7a629-803c-4048-8944-1a2f80a0bf39" />

# %	      Modulus (remainder)

<img width="584" height="232" alt="image" src="https://github.com/user-attachments/assets/f4ba5933-ea53-4563-8590-5fd29227be9b" />

















                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
