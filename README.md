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
- **SQLite file link:** [WSDA Music Sales Data Analysis](https://github.com/TanishaMitra18/Data-Analysis-using-SQL-and-PowerBi/blob/86b20a9d6e33312fa1982fe68ac2b99fdac71a6f/WSDA_Music.sqbpro)
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

### Images for Reference

![image-url.png](https://github.com/TanishaMitra18/Data-Analysis-using-SQL-and-PowerBi/blob/86b20a9d6e33312fa1982fe68ac2b99fdac71a6f/WSDA%20Music_moneyproblem01.png)

![image-url.png](https://github.com/TanishaMitra18/Data-Analysis-using-SQL-and-PowerBi/blob/86b20a9d6e33312fa1982fe68ac2b99fdac71a6f/WSDA%20Music_moneyproblem02.png)

### Sqlite file User Instructions
- **SQLite file link:** [WSDA Music_Missing Money Problem](https://github.com/TanishaMitra18/Data-Analysis-using-SQL-andPowerBi/blob/1e25ab4e79926a80fe50c6743d6bf54ed6de6d0d/WSDA_Find%20Missing%20Money.sqbpro)
- Query Description/Question mentioned in the file
- Query Code mentioned below query descriptions

## Project 3: Business Performance Analytics Report (SQL + Power BI)

- Built a SQL project with Power BI integration for data visualization and reporting.
- Combines SQL queries + interactive visuals for executives, managers, and analysts.
- Focus on revenue, customers, products, stores, staff, and inventory.

### Report Contents

**Tab 1: Executive Overview**
- KPIs: Revenue, Orders, Customers, Avg Order Value
- Revenue trend by month
- Top 10 products by revenue
- Revenue by city/state

**Tab 2: Customer & Product Insights**
- New vs Returning customers
- Top 10 customers by lifetime value
- Revenue by category
- Revenue by brand
- Yearly trend for top 10 products

**Tab 3: Store, Staff & Inventory**
- Revenue per store
- Staff performance
- Stock levels by store & product
- Out‑of‑stock alerts (Highlight turns 'Red' once Stock reaches zero)
- Inventory vs demand

### Report Highlights
- Designed an end-to-end interactive Power BI dashboard using the bike sales dataset.
- Analysed 8.58M+ revenue, 1M customers, and 1.6K orders using key KPIs.
- Built state-wise revenue heatmap to identify high-performing regions (CA, TX, NY).
- Identified Top 10 revenue-generating products and yearly sales trends (2016–2018).
- Performed customer segmentation to compare one-time vs regular customers.
- Compared brand and category-wise performance to highlight best-selling brands (Trek, Electra, Surly).
- Added employee-level performance metrics to track sales efficiency.
- Monitored store-wise revenue, inventory levels, and demand vs supply patterns.
- Created interactive slicers to filter by product and store for deeper insights.
- Delivered a complete business insights view covering sales, operations, and customer behavior.

### Tech Stack
- SQL → data modeling & queries
- MS Excel → Importing Data
- Power BI → visualization & dashboards

### Files and Links attached for Reference
- **Dataset Source:** [Bike Sales Analystics](https://www.kaggle.com/datasets/dillonmyrick/bike-store-sample-database)
- 

