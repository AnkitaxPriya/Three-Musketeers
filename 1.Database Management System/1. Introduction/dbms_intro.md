# Database Management System 

A database management system is a collection of software that provides one a quick way to access and modify the data. 

Popular examples of database management system:
- Oracle 
- MySQL
- Sybase
- Microsoft SQL Server

# Evolution of DBMS
## File based system 
File System manages data using files in hard disk. Here, user code directly interacts with the file system of the OS. 
Problems faced: 
- Redundancy of data
- Inconsistency of data
- Difficult to access data
- No backup and recovery 

## Relational DBMS
Stores data in the form of **table**. Each table has a schema(header of the table) which defines how each row should be. Here, relational DBMS acts as a software between the user code and the file system to read and write the data. It is the most widely used DBMS.

Examples: Oracle, MySQL, PostgreSQL, SQL server,...

Structured Query Language:
It is a 4th generation programming language provided by Relational DBMS. SQL allows user code to access the data and to modify the data in a very convenient way. 

Features of Relational DBMS:
- Provides all the services to access and modify the data. 
- Have an administration panel to assign the user its roles. 
- Scores are given to handle concurrency.

Challenges in Relational DBMS:
- Scalability
- Have a proper structure

## NoSQL 
They do not require any structure and are scalable horizontally. One can create multiple copies of the DBMS. *They're NOT a replacement of RDBMS.*
Data stored here does not have to be a table. They are in the form of documents, objects, etc.
Examples: MongoDB, DynamoDB, Cassandra, ...

Challenges in NoSQL:
- No consistency in transactions. 