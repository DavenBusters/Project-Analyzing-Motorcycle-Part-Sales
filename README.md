# Project-Analyzing-Motorcycle-Part-Sales
This repository contains the SQL code and documentation for a project completed as part of the DataCamp certification as an Associate Data Analyst in SQL. The project revolves around analyzing sales data for a company specializing in motorcycle parts.

Description:

This repository contains the SQL code and documentation for a project completed as part of the DataCamp certification as an Associate Data Analyst in SQL. The project revolves around analyzing sales data for a company specializing in motorcycle parts.

Project Overview:

The company operates three warehouses, selling both retail and wholesale. The analysis focuses on wholesale revenue by product line, examining variations across different months and warehouses. The goal is to provide insights into the net revenue generated by each product line, grouped by month and warehouse, specifically focusing on wholesale orders.

Dataset Description:

The primary dataset, named sales, includes the following columns:

order_number: Unique identifier for each order.
date: Date of the order, ranging from June to August 2021.
warehouse: The location where the order originated, categorized into North, Central, or West.
client_type: Identifies whether the order is Retail or Wholesale.
product_line: Type of motorcycle parts ordered.
quantity: Number of products ordered.
unit_price: Price per product in dollars.
total: Total price of the order in dollars.
payment: Payment method used, including Credit card, Transfer, or Cash.
payment_fee: Percentage of the total charged as a fee based on the payment method.
Project Tasks:

The main task involves calculating the net revenue for each product line, grouped by month and warehouse, with a focus on wholesale orders. This requires filtering the dataset to include only wholesale orders and performing the necessary calculations to determine net revenue. The output is formatted to present the results in a clear and structured manner, facilitating easy interpretation and decision-making by the company's board of directors.

Query Output Format:

The query output is presented in the following format:

product_line	month	warehouse	net_revenue
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_two	---	---	---
...	...	...	...
Project Files:

SQL Code: Contains the SQL queries used to perform data analysis and generate the required results.
Documentation: Includes detailed explanations of the analysis approach, query logic, and interpretation of results.
Conclusion:

This project provides valuable insights into wholesale revenue patterns for motorcycle parts across different product lines, months, and warehouses. The analysis assists the company in making informed decisions to optimize sales strategies and maximize revenue generation.
