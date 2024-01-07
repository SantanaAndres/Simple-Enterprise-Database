# Enterprise Database

This repository contains the SQL script to create a simple enterprise database with tables for departments, projects, employees, employee projects, employee phones, and employee mails. This database is designed to manage information about employees, their departments, and their involvement in various projects.

## Tables

### Department:

- DEPARTMENT_ID (Primary Key)
- DEPARTMENT_NAME

### Projects:

- PROJECT_ID (Primary Key)
- PROJECT_NAME

### Employees

- EMPLOYEE_ID (Primary Key)
- F_NAME
- L_NAME
- DEPARTMENT_ID (Foreign Key referencing Department)
- IDENTIFICATION_CARD (Unique) with format check

### Employee Projects

- PROJECT_ID (Foreign Key referencing PROJECTS)
- EMPLOYEE_ID (Foreign Key referencing Employees)

### Employee Phones

- PHONE_ID (Primary Key)
- EMPLOYEE_ID (Foreign Key referencing Employees)
- PHONE

### Employee Mails:

- MAIL_ID (Primary Key)
- EMPLOYEE_ID (Foreign Key referencing Employees)
- MAIL

## Usage

<ol>
<li>Create a database named "Enterprise."</li>
<li>Use the "Enterprise" database.</li>
<li>Run the SQL script to create the tables.</li>
<li>Feel free to modify the script according to your specific requirements and business logic.</li>
</ol>
