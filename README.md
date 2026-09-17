Adventure Works – SQL Data Analysis

📌 Project Overview

This project analyzes the Adventure Works dataset using MySQL to perform data integration, relational analysis, date analysis, and business calculations.

 🎯 Objectives

- Combine sales datasets
- Perform SQL joins between fact and dimension tables
- Retrieve product and customer information
- Create date and financial period fields
- Calculate sales amount
- Calculate production cost
- Calculate profit

 🛠️ Tools Used

- MySQL
- SQL
- Data Analysis
- Data Cleaning
- Joins
- Date Functions
- Aggregate & Calculated Fields

📊 SQL Analysis

The project covers:

 Q0 – Combine Sales Data
Combined `FactInternetSales` and `Fact_Internet_Sales_New` using `UNION ALL`.

 Q1 – Product Lookup
Used a `LEFT JOIN` to retrieve product names from the product dimension.

 Q2 – Customer & Product Analysis
Joined customer and product tables to retrieve customer names and unit prices.

 Q3 – Date Analysis
Created:
- Order Date
- Year
- Month
- Quarter
- Year-Month
- Weekday
- Financial Month
- Financial Quarter

 Q4 – Sales Amount

Sales Amount is calculated as:

`(Unit Price × Order Quantity) − Discount Amount`

 Q5 – Production Cost

Retrieved production cost using `TotalProductCost`.

 Q6 – Profit

Profit is calculated as:

`Sales Amount − Production Cost`

💡 Skills Demonstrated

- SQL Joins
- UNION ALL
- Date & Time Functions
- CASE Statements
- String Functions
- Calculated Fields
- Business Analysis
- Relational Database Analysis

 📁 Project File

Adventure_Works_SQL_Q0_Q6 (2).sql

👤 Author
  santhosh Kumar

**Santhosh Kumar**

Aspiring Data Analyst | Business Analytics
