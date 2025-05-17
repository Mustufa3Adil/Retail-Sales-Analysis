# Retail-Sales-Analysis
A retail sales analysis project using SQL. Includes data cleaning, shift-wise order trends, category breakdowns, and customer behavior analysis across time.

# 🛍️ Retail Sales Data Analysis – SQL Project

This SQL project explores transactional retail sales data by cleaning and analyzing customer behavior, sales performance, and shift-wise trends. The goal is to extract insights useful for business strategy and decision-making.

---

## 📊 Dataset Overview

The dataset includes detailed retail transactions, with attributes such as:

- Transaction ID
- Sale Date & Time
- Customer ID, Gender, Age
- Product Category
- Quantity & Price
- Cost of Goods Sold (COGS)
- Total Sale

---


```sql
CREATE TABLE retail_sales (
    transactions_id INT PRIMARY KEY,
    sale_date DATE,	
    sale_time TIME,
    customer_id INT,	
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,	
    cogs FLOAT,
    total_sale FLOAT
);
