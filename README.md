# Sql_Employee_Project
# Employee Database SQL Queries

This project contains SQL queries to manage and analyze data in an **Employee Database**. The database, titled `employees`, includes information about employees' IDs, names, departments, salaries, and joining dates. The SQL queries included in this project perform various operations, such as updating column names, filtering records, aggregating data, and updating specific records.

## Project Structure

- `employees.sql`: Contains SQL queries for managing and analyzing the employee database.
- `README.md`: This file, providing an overview of the project and explanations for each query.

## Table Structure

After renaming the columns, the `employees` table has the following structure:

| Column       | Description               |
|--------------|---------------------------|
| EmployeeID   | Unique identifier for each employee |
| Name         | Name of the employee      |
| Department   | Department of the employee |
| Salary       | Salary of the employee    |
| JoiningDate  | Date when the employee joined |

## Queries Overview

### Table Modification Queries

1. **Rename Columns**: Renames the columns for better readability.
   ```sql
   ALTER TABLE employees RENAME COLUMN c1 TO EmployeeID;
   ALTER TABLE employees RENAME COLUMN c2 TO Name;
   ALTER TABLE employees RENAME COLUMN c3 TO Department;
   ALTER TABLE employees RENAME COLUMN c4 TO Salary;
   ALTER TABLE employees RENAME COLUMN c5 TO JoiningDate;
