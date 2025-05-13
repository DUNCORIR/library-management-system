Library Management System

Project Description
This project implements a complete relational **Library Management System** using **MySQL**. It models real-world entities such as books, authors, members, categories, and book loans.

The database:
- Tracks books and their authors
- Organizes books by categories
- Manages library members and book loans
- Handles many-to-many relationships using junction tables

How to Run / Setup

1. Install MySQL (Workbench or CLI).
2. Clone this repository:
   ```bash
   git clone https://github.com/duncorir/library-management-system.git
   cd library-management-system
Open library_schema.sql in your SQL environment and run the script to create all tables.

Ensure you have a database created before running the SQL:

sql
CREATE DATABASE library_db;
USE library_db;
ER Diagram

You can create and export the ERD using tools like dbdiagram.io, [MySQL Workbench], or DrawSQL.

File Description
library_schema.sql: Contains all CREATE TABLE statements with relationships and constraints, including inline comments for clarity.

Author: Duncan Korir
