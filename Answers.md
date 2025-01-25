-- Question 1
I}Query Processor: Interprets and executes the SQL queries issued by users or applications.

II}Database Manager: Responsible for managing the database's structure and providing access control, ensuring the database's security and consistency.

III}Transaction Manager: Ensures that database transactions are executed in a way that maintains consistency, isolation, durability, and atomicity (ACID properties).

IV}Data Dictionary: Stores metadata, which includes definitions of tables, columns, data types, constraints, and relationship

V} Database Schema: Defines the logical structure of the database, including tables, relationships, views, and indexes.


--Question 2
i} relational database is a type of database that stores data in tables with rows and columns. Each table represents a specific entity or concept, and each row represents a record in that entity. Columns represent attributes or properties of the entity.  Relational databases enforce relationships between tables using primary keys and foreign keys. Here are four examples of relational database

Examples of relational databases:

MySQL

PostgreSQL

Oracle Database

Microsoft SQL Server

--Question 3
I}DDL (Data Definition Language):

Used to define and manage the structure of a database.

Examples: CREATE, ALTER, DROP

Explanation: DDL commands create, modify, and delete database structures such as tables, indexes, and views.

II]DML (Data Manipulation Language):

Used to retrieve, insert, update, and delete data in the database.

Examples: SELECT, INSERT, UPDATE, DELETE

Explanation: DML commands are used for data manipulation within the database, allowing users to query, add, modify, and remove data.

ii}DCL (Data Control Language):

Used to control access to data within the database.

Examples: GRANT, REVOKE

Explanation: DCL commands manage permissions and access control, ensuring that only authorized users can perform specific operations on the database.

--  Question 4
Primary Key: A unique identifier for each record in a database table. It must contain unique values and cannot contain NULL values. Each table can have only one primary key.

Foreign Key: A field (or a set of fields) in one table that uniquely identifies a row of another table. It creates a link between two tables, enforcing referential integrity.

--Question 5
What is an Entity-Relationship Diagram (ERD)?

An Entity-Relationship Diagram (ERD) is a visual representation of the relationships between different entities (tables) in a database. It uses graphical symbols to depict entities, attributes, and their relationships.

Entities: Entities represent the main objects or concepts within the database (e.g., Customers, Products, Orders).
Attributes: Attributes are the properties or characteristics of an entity (e.g., Customer ID, Customer Name, Product Name, Price).
Relationships: Relationships define how entities are connected to each other (e.g., one-to-one, one-to-many, many-to-many).

--Question 6
What are the Advantages of Relational Databases?

i}Data Integrity: Ensures accuracy and consistency of data through constraints and relationships.

ii}Flexibility: Allows complex queries and easy updates to the database structure.

iii}Scalability: Can handle large amounts of data and concurrent users.

IV}Security: Provides robust access control and permissions management.

V}Standardization: Uses SQL, a widely accepted and standardized query language.

--Question 7
I]Integer: Stores whole numbers without decimal points.

Examples: INT, SMALLINT

II}Floating Point: Stores numbers with decimal points.

Examples: FLOAT, DOUBLE

III}Character/String: Stores text data.

Examples: CHAR, VARCHAR

IV}Date/Time: Stores dates and times.

Examples: DATE, TIME, TIMESTAMP

--Question 8
What is the Purpose of a Database Management System (DBMS)?
The purpose of a DBMS is to provide an efficient, reliable, and secure way to store, retrieve, and manage data. It offers tools and functionalities to maintain data integrity, enforce security, and allow for easy access and manipulation of data. A DBMS ensures that data is organized, accessible, and maintainable
