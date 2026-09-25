# SQL Course

A beginner-friendly SQL learning repository inspired by the video tutorial: https://youtu.be/SSKVgrwhzus

This repo is meant to help learners build a strong foundation in SQL through structured study material, practical examples, and downloadable resources.

## About the Course

SQL (Structured Query Language) is the standard language used to interact with relational databases. It allows you to:

- Create and manage databases
- Store and organize data
- Retrieve information with queries
- Update and delete data safely
- Join tables and analyze relationships

This course is designed for beginners who want to learn SQL step by step with simple explanations and hands-on practice.

## What You Will Learn

- SQL basics and database fundamentals
- Creating tables and databases
- Inserting, updating, and deleting data
- Selecting data using `SELECT`
- Filtering data with `WHERE`
- Sorting results using `ORDER BY`
- Grouping and aggregating data with `GROUP BY`
- Applying conditions using `HAVING`
- Joining multiple tables
- Using subqueries and nested queries
- Working with constraints and data integrity
- Writing practical SQL queries for real-world use cases

## Repository Structure

```text
SQL-course/
├── sql-mylearnings/
│   └── PDFs/
│       └── 01_SQL_Introduction.pdf
└── README.md
```

## Course Materials

The repository currently includes:

- `sql-mylearnings/PDFs/01_SQL_Introduction.pdf` — introduction to SQL fundamentals

## Recommended Learning Flow

1. Watch the YouTube tutorial linked above
2. Read the PDF materials in the repository
3. Practice SQL queries in a local database
4. Try writing your own queries on sample datasets
5. Build small projects to reinforce the concepts

## Prerequisites

To practice SQL effectively, you should have access to any of the following:

- MySQL
- PostgreSQL
- SQL Server
- SQLite

You can use tools like:

- MySQL Workbench
- pgAdmin
- DBeaver
- SQL Server Management Studio

## Getting Started

Install a SQL database management system and start writing queries like:

```sql
SELECT *
FROM employees;
```

```sql
SELECT name, salary
FROM employees
WHERE salary > 50000
ORDER BY salary DESC;
```

```sql
SELECT department, COUNT(*)
FROM employees
GROUP BY department;
```

## Why Learn SQL?

SQL is one of the most valuable skills in data, software development, analytics, and business intelligence. It is used in:

- Web applications
- Data analysis
- Reporting and dashboards
- Backend systems
- Data engineering

## Contribution

This repository is a learning resource. If you want to expand it with more SQL notes, practice questions, or additional PDF materials, feel free to contribute.

## License

This project is currently provided as a personal learning resource and does not include a formal license unless added later.

## Connect

- YouTube: https://youtu.be/SSKVgrwhzus
- GitHub: https://github.com/dhrumibhatia/SQL-course

---

“Learn SQL, write better queries, and unlock the power of data.”
