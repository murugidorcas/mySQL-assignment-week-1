# mySQL-assignment-week-1


### Components of a DBMS (Database Management System)

A DBMS is a software system designed to manage databases. It consists of the following components:

1. **Database Engine**: Provides the core services for accessing and processing data stored in the database. It handles data storage, retrieval, and update operations.
2. **Database Schema**: Defines the logical structure of the database, including tables, columns, data types, and relationships among data. It acts as a blueprint for how data is organized.
3. **Query Processor**: Interprets and executes database queries written in SQL (Structured Query Language). It optimizes query execution to retrieve data efficiently.
4. **Transaction Manager**: Ensures that database transactions are processed reliably and maintain the ACID (Atomicity, Consistency, Isolation, Durability) properties, which guarantee data integrity.
5. **Database Management Tools**: Provides user interfaces and tools for database administration, including tools for backup, recovery, performance tuning, and security management.

### What is a Relational Database?

A relational database is a type of database that stores data in tables (relations), where each table is a collection of rows and columns. The data in relational databases is organized based on relationships defined by keys. Examples of relational databases include:

1. **MySQL**
2. **PostgreSQL**
3. **Oracle Database**
4. **Microsoft SQL Server**

### Classifications of SQL

1. **DDL (Data Definition Language)**: Used to define and manage database structures. Examples: `CREATE`, `ALTER`, `DROP`.
   - **Example**: `CREATE TABLE Students (ID INT, Name VARCHAR(50));`

2. **DML (Data Manipulation Language)**: Used for data manipulation within the database. Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
   - **Example**: `INSERT INTO Students (ID, Name) VALUES (1, 'John Doe');`

3. **DCL (Data Control Language)**: Used to control access to data within the database. Examples: `GRANT`, `REVOKE`.
   - **Example**: `GRANT SELECT ON Students TO user1;`

### Difference between a Primary Key and a Foreign Key

- **Primary Key**: A unique identifier for each record in a table. It ensures that no two rows have the same primary key value.
  - Example: In a `Students` table, `StudentID` could be the primary key.
  
- **Foreign Key**: A field in one table that references the primary key in another table, establishing a relationship between the two tables.
  - Example: In an `Enrollments` table, `StudentID` could be a foreign key that references the `StudentID` in the `Students` table.

### What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a graphical representation of entities and their relationships in a database. It helps visualize the structure of the database, showing tables (entities), columns (attributes), and relationships (connections) between them.

### Advantages of Relational Databases

1. **Data Integrity**: Ensures accuracy and consistency of data through constraints and relationships.
2. **Flexibility**: Allows for complex queries and data manipulation using SQL.
3. **Scalability**: Can handle large amounts of data and support multiple users simultaneously.
4. **Security**: Provides robust mechanisms for data access control and user authentication.

### Four Types of Data Types Used to Store Data in Tables

1. **INTEGER**: Used to store whole numbers.
   - Example: `INT` or `BIGINT`
2. **VARCHAR**: Used to store variable-length strings.
   - Example: `VARCHAR(255)`
3. **DATE**: Used to store date values.
   - Example: `DATE`
4. **BOOLEAN**: Used to store true/false values.
   - Example: `BOOLEAN`

### Purpose of a Database Management System (DBMS)

The purpose of a DBMS is to provide a systematic and efficient way to create, store, retrieve, and manage data in databases. It offers functionalities for data manipulation, query processing, transaction management, and security, ensuring data integrity and consistency while supporting multiple users and applications.

