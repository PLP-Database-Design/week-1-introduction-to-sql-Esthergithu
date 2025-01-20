State and Explain the components of a DBMS(Database Management System)

Database Engine: Manages data storage, retrieval, and manipulation.
Database Schema: Defines the logical structure of the database (tables, relationships, constraints).
Query Processor: Interprets and executes database queries.
Transaction Manager: Ensures data integrity through ACID properties (Atomicity, Consistency, Isolation, Durability).
Data Dictionary: Metadata repository storing details about the database structure.
Concurrency Control: Manages simultaneous access to ensure consistency.
Backup and Recovery: Maintains data safety and restoration mechanisms.
User Interface: Allows interaction with the database through commands or GUI.

What is a relational database? Give 4 examples.

A type of database that organizes data into tables(relations) consisting of rows(records) and columns(fields).  It uses structured query language (SQL) for defining, querying, and managing data and relies on relationships between tables through keys (primary and foreign keys).

Examples of Relational Databases:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server

State and Explain three classifications of SQL?

Data Definition Language (DDL):

Defines and modifies the structure of database objects such as tables, indexes, and schemas.
Common commands:
CREATE (create a new table or database)
ALTER (modify existing database structures)
DROP (delete tables or databases)
Data Manipulation Language (DML):

Deals with the manipulation and retrieval of data within tables.
Common commands:
SELECT (retrieve data)
INSERT (add new data)
UPDATE (modify existing data)
DELETE (remove data)
Data Control Language (DCL):

Manages access and permissions for database users.
Common commands:
GRANT (give access rights to users)
REVOKE (remove access rights from users)

What is the difference between a Primary Key and a Foreign Key?

Aspect	    Primary Key	                                Foreign Key
Definition	Uniquely identifies each record in a table.	Establishes a relationship between two tables.
Uniqueness	Must be unique for every record.	        Can have duplicate values (matches primary key values in the related table).
Nullability	Cannot contain NULL values.	                Can contain NULL values if not required.
Purpose	    Enforces entity integrity.	                Enforces referential integrity.
Location	Defined in the same table it identifies.	References a primary key in another table.

What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of the structure and relationships within a database. It illustrates how entities (tables) are related to each other through relationships and defines the data's structure logically.

Advantages of relational databases

Data Integrity: Ensures accuracy and consistency of data through constraints like primary keys and foreign keys.

Flexibility: Easy to modify the database schema or add new data without disrupting existing operations.

Ease of Use: Uses SQL, a widely adopted and easy-to-learn language, for querying and managing data.

Data Relationships: Efficiently manages relationships between data using tables and keys.

Scalability: Supports large datasets and concurrent access by multiple users.

Data Security: Offers robust access controls and permissions for data protection.

Standardization: Adheres to industry standards, making it compatible with various tools and applications.

Backup and Recovery: Provides mechanisms for data backup and recovery in case of failure.

Minimized Data Redundancy: Normalization reduces duplicate data, optimizing storage.


State four types of data type used to store data in tables?

Integer (INT):

Used to store whole numbers.
Example: 1, 42, 1000.

Character/String (CHAR, VARCHAR, TEXT):

Used to store text data.
Example: Names, descriptions ('John', 'Hello World').

Date/Time (DATE, TIME, DATETIME, TIMESTAMP):

Used to store date and time values.
Example: 2025-01-18, 12:45:00.

Floating Point/Decimal (FLOAT, DOUBLE, DECIMAL):

Used to store numbers with decimal points.
Example: 3.14, 99.99.

What is the purpose of a database management system (DBMS)?

The purpose of a Database Management System (DBMS) is to provide a systematic and efficient way to store, manage, and retrieve data. It acts as an intermediary between users and databases, ensuring data is accessible, secure, and organized.
Key Purposes:
Data Storage and Retrieval: Efficiently stores large volumes of data and allows for quick retrieval.
Data Organization: Structures data into tables with relationships for easier management.
Data Integrity: Maintains accuracy and consistency through constraints and rules.
Data Security: Protects sensitive information with user authentication and permissions.
Concurrency Control: Manages simultaneous access by multiple users without conflicts.
Backup and Recovery: Ensures data safety and supports restoration in case of failures.
Data Abstraction: Hides complex details, providing a user-friendly interface for interaction.