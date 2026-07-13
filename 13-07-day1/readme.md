# Student Database SQL Queries 13-07-day1

## Overview

This project demonstrates SQL operations performed on a **Students** database using MySQL. It covers fundamental to advanced SQL concepts, including data retrieval, filtering, sorting, aggregation, column transformations, window functions, and pivot tables.

## Objectives

- Create and populate a relational database table
- Retrieve data using SQL queries
- Filter and sort records
- Handle NULL values
- Perform column transformations
- Apply aggregate functions
- Analyze data using GROUP BY
- Use window functions for ranking
- Create pivot tables for reporting

## Technologies Used

- MySQL 8.0
- SQL
- MySQL Workbench

## Dataset

### Table: Students

The dataset contains student information with the following attributes:

- Student ID
- Student Name
- Department
- City
- Marks
- Attendance

## SQL Workflow

### 1. Data Definition

- Create Students table
- Define primary key
- Specify appropriate data types

### 2. Data Insertion

- Insert student records
- Include NULL values for practice

### 3. Data Analysis

- Retrieve records
- Filter and sort data
- Perform aggregations
- Generate reports

---

# SQL Exercises

## Section A – Basic Level

### Exercise 1
Display the first five rows of the dataset.

### Exercise 2
Count the total number of rows and columns.

### Exercise 3
Find missing values in each column.

### Exercise 4
Replace NULL values in the marks column with the average marks.

### Exercise 5
Display only the student name and marks columns.

---

## Section B – Filtering & Sorting

### Exercise 6
Display students scoring more than 160 marks.

### Exercise 7
Display students from the CS department.

### Exercise 8
Find students with attendance greater than 85 and marks greater than 150.

### Exercise 9
Sort students by marks in descending order.

### Exercise 10
Display the top three students based on marks.

---

## Section C – Column Transformations

### Exercise 11
Calculate the percentage assuming total marks are 200.

### Exercise 12
Assign grades using CASE statements.

### Exercise 13
Add five bonus marks to every student.

### Exercise 14
Generate Pass/Fail results based on percentage.

### Exercise 15
Convert all student names to uppercase.

---

## Section D – GroupBy & Aggregation

### Exercise 16
Calculate the average marks of each department.

### Exercise 17
Find the maximum marks scored in each city.

### Exercise 18
Count the number of students in each department.

### Exercise 19
Identify the department with the highest average marks.

### Exercise 20
Create a pivot table showing average marks by department and city.

---

## Section E – Advanced SQL

### Exercise 21
Rank students based on marks.

### Exercise 22
Find students whose marks are above the overall average.

### Exercise 23
Standardize marks using Min-Max Scaling.

### Exercise 24
Categorize attendance into:
- Excellent
- Good
- Average
- Poor

---

## SQL Concepts Covered

- SELECT
- WHERE
- ORDER BY
- LIMIT
- COUNT()
- AVG()
- MAX()
- SUM()
- GROUP BY
- CASE
- UPDATE
- Subqueries
- Window Functions (RANK)
- Pivot Tables
- Aggregate Functions
- NULL Handling

---

## Learning Outcomes

- Create and manage SQL tables
- Write efficient SELECT queries
- Filter and sort records
- Handle missing values
- Perform aggregate analysis
- Use GROUP BY and HAVING
- Apply CASE statements
- Work with subqueries
- Use window functions for ranking
- Generate pivot-style reports
- Perform data transformation using SQL

---

## Project Structure

```
SQL-Student-Database/
│── Student_Database.sql
│── SQL_Queries.sql
└── README.md
```

## Author

**Vyshnavi Dharmaraju**
