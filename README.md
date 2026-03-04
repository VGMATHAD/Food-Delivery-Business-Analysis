🍽️ Food Delivery Business – SQL Data Analysis Project

📌 Project Overview
This project focuses on designing and analyzing a Food Delivery Business database using SQL. The goal was to extract meaningful business insights from raw order data and support data-driven decision-making.

🗄️ Database Schema
The project consists of the following tables:
1️⃣ FOOD_CUSTOMERS
CUSTOMER_ID (Primary Key)
CUSTOMER_NAME
CITY
SIGNUP_DATE

2️⃣ FOOD_RESTAURANTS
RESTAURANT_ID (Primary Key)
RESTAURANT_NAME
CITY
CUISINE_TYPE

3️⃣ FOOD_DELIVERY_PARTNERS
PARTNER_ID (Primary Key)
PARTNER_NAME
CITY
JOINING_DATE

4️⃣ FOOD_ORDERS
ORDER_ID (Primary Key)
CUSTOMER_ID (Foreign Key)
RESTAURANT_ID (Foreign Key)
PARTNER_ID (Foreign Key)
ORDER_DATE
ORDER_AMOUNT
DELIVERY_TIME_MINUTES
ORDER_STATUS

🎯 Business Objectives
The analysis answers key business questions:
What is the total revenue generated?
What is the average order value
Which restaurants generate the most revenue?
Who are the top customers?
How efficient are delivery partners?
What are the monthly revenue trends?
How many repeat customers does the business have?

📊 Key Performance Indicators (KPIs)
Total Customers
Total Orders
Total Revenue
Average Order Value (AOV)
Average Delivery Time

🔎 SQL Concepts Used
CREATE DATABASE & CREATE TABLE
Primary and Foreign Keys
INNER JOIN
GROUP BY
ORDER BY
HAVING
Aggregation Functions (SUM, COUNT, AVG)
LIMIT
Date functions (EXTRACT)

📈 Analytical Insights

✔️ Identified Top 5 Restaurants by Revenue
✔️ Found Top 5 Customers by Spending
✔️ Measured Delivery Partner Efficiency
✔️ Analyzed Monthly Revenue Trends
✔️ Calculated Customer Retention

🛠️ Tools Used

SQL (MySQL / SQL Server)

Relational Database Design

🚀 Future Improvements
Add Power BI dashboard visualization
Implement advanced SQL (Window Functions)
Perform Customer Segmentation
Add profitability analysis

👨‍💻 Author

Vaibhav Mathad
Aspiring Data Analyst | SQL | Power BI | Data Visualization
