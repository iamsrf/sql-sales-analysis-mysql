# Online Book Store - SQL Data Analysis Project

## 1. Project Overview 
This project simulates an online bookstore database containing information about books, customers and orders. The objective was to analyze sales performance, customer activity, and inventory insights using MYSQL Workbench.

## 2. Database Description 
The database consist of the following tables:

- Books (book_id, title, stock, price)
- Customers (customer_id, name, email , contact numbers , city, country)
- Orders (order_id, customer_id, book_id, quantity, order_date)

These tables are connected using primary and foreign key relationships.

## 3. Business Questions Solved 
Some of the analysis performed includes:

- Total revenue generated
- Most sold books
- Customers with highest numbers of orders
- Average order value
- Books with low stock 
- Sales grouped by customers
- customers who placed more than x orders (using HAVING)

## 4. SQL Concepts Used
- INNER JOIN
- LEFT JOIN
- GROUP BY
- HAVING
- ORDER BY
- SUM()
- AVG()
- Aggregations
- Filtering conditions

## 5. Key Insights
 - Identified top-performing by quantity sold
 - Determined most active customers
 - Calculated overall and average revenue metrics
 - Detected low stock inventory items

## 6. Files Included
- schema.sql (database and table creation)
- analysis_queries.sql (all solved sql queries)
- CSV Files
- README.md

## 7. How to Run This Project
1. Import schema.sql into MySQL
2. Insert data
3. Run analysis_queries.sql to reproduce the analysis

## Notes
Project inspired by a PostgreSQL tutorial but independently implemented in MySQL 
