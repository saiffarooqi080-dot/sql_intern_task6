## Objective
The goal of this task was to demonstrate proficiency in using subqueries in different clauses of a SQL query—SELECT, WHERE, and FROM—to achieve complex data filtering and analysis logic.

## Database Design: The Library System
The same simple Library System from Task 5 was utilized:
* **Authors** table
* **Books** table (linked to Authors via `AuthorID`)

## Deliverables
All SQL queries were executed in MySQL Workbench and categorized by their placement and type of subquery.

### Files in this Repository
* `task_6_subqueries.sql`: Contains the database setup, data insertion, and all required subquery examples.
* `interview_answers.md`: Detailed answers to the key SQL Subquery interview questions.
* `task_log.md`: A summary of the steps taken to complete the task.

## Key Concepts Demonstrated
* **Subqueries in WHERE**: Filtering using `IN`, comparison operators (`>`), and `EXISTS`.
* **Scalar Subqueries**: Returning a single value for correlation or comparison.
* **Correlated Subqueries**: Inner query depends on the outer query's row data.
* **Derived Tables**: Subquery used in the `FROM` clause, acting as a temporary, on-the-fly table.
