# Student Management System (Java + MySQL)

A console-based application to manage student records using Java and MySQL.

## Features
- Add student
- View students
- Update student details
- Delete student
- Data stored permanently using MySQL

## Technologies Used
- Java
- MySQL
- JDBC (MySQL Connector)

## Project Structure
- StudentSystem.java
- Student.java

## Setup Instructions
1. Install MySQL and create database:
   CREATE DATABASE student_db;

2. Create table:
   CREATE TABLE students (
       id INT PRIMARY KEY,
       name VARCHAR(100),
       age INT,
       course VARCHAR(100)
   );

3. Add MySQL Connector JAR to project

4. Update DB password in code:
   String password = "your_password";

5. Run StudentSystem.java

## Learning Outcomes
- JDBC connection handling
- CRUD operations
- Database integration in Java