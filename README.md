# IMDB-SQL-Project

SQL project analyzing IMDB movies and directors using queries, joins, and aggregations.

## About
This project creates two tables (`movies` and `directors`), loads data into them, and answers 13 questions about the data using SQL. It also builds a merged table (`movies_directors`) that combines both tables.

## Tables
- **directors**: name, id, gender, uid, department
- **movies**: movie details such as budget, revenue, popularity, and average vote
- **movies_directors**: movies and directors joined into one table

## Questions Answered
1. Get all data about movies and directors
2. Count how many movies are in the database
3. Find specific directors (James Cameron, Luc Besson, John Woo)
4. Find directors whose name starts with "S"
5. Count female directors
6. Find the first 10 women directors
7. Find the 3 most popular movies
8. Find the 3 most bankable movies (highest profit)
9. Find the highest average vote since January 1st, 2000
10. Find movies directed by Brenda Chapman
11. Find which director made the most movies
12. Find the most bankable director
13. Create a merged table of movies and directors

## SQL Concepts Used
`SELECT`, `WHERE`, `LIKE`, `ORDER BY`, `LIMIT`, `GROUP BY`, `HAVING`, `JOIN`, `COUNT`, `SUM`, subqueries, `CREATE TABLE AS`

## How to Run
1. Open MySQL Workbench (or any MySQL client)
2. Create the database: `CREATE DATABASE imdb_project;`
3. Open `sql_queries/sql_queries.sql`
4. Run the file

## Author
pmounikaa
