# Data-Analysis-using-SQL-and-PowerBi
This repository contains data analysis projects using SQL and PowerBi. 
- SQL is used for data cleaning, querying and analysis.
- PowerBi is used for reporting and visual exploration to provide meaningful insights.

## Project 1: WSDA Music Sales Data Analysis
- **Tools used:** SQLite
- **Dataset Source:** SQL Essential Training (Linkedin Learning)
- 
### Highlights
- Use of `JOIN` and subqueries to filter and combine data.
- Creation of views (`CREATE VIEW`) to simplify repeated queries.
- Application of aggregate functions (`AVG`, `COUNT`, `ROUND`) for reporting.
- Exploration of query optimization using `WITH` clauses (CTEs).

### Learning Goals
- Strengthen understanding of SQL syntax and operator precedence.
- Practice writing clean, reusable, and efficient queries.

### Sqlite file User Instructions
- **SQLite file link:** 
- Query Description/Question mentioned in the file.
- Query Code mentioned below all query descriptions.

## Project 2: WSDA Music_Missing Money Problem
- **Tools used:** SQLite
- **Dataset Source:** SQL Essential Training (Linkedin Learning)

### Problem Statement
For a long time, Adams Andrew, Manager of WSDA Music, has been unable to account for a discrepancy in his company’s financials.
The furthest he has gotten in his own attempts to analyze the company data is figuring out that the discrepancy occurred between the years 2011 and 2012. But that’s about all that Adams knows for certain.

### Solution
- Finding the total and average money spent by customers in WSDA Music to look for dicrepancies.
- Then we find the customer and support rep associated with the highest total invoice.
- Query shows customer John Doeein's average expenditure is evidently very high compared to other customers, i.e., 1000 dollars compared 11 dollars of total average grouped by Customer Id as well as 1000 dollars were spent in one invoice itself, despite the fact that a single track costs not more than 0.99 dollars.
- Thus, **John Doeein** becomes the primary person of interest for us.
- Other discrepancies can be missing email id of the customer and similarity in customer's name and support representative's name.

### Sqlite file User Instructions
- **SQLite file link:** 
- Query Description/Question mentioned in the file
- Query Code mentioned below query descriptions
