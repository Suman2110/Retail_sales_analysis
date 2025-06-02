# 🛍️ Retail Sales Analysis (SQL Project)

Welcome to the **Retail Sales Analysis** SQL project!  
This project is designed to showcase practical SQL skills by analyzing retail transaction data to uncover sales trends, customer behavior, and business insights.

## 📁 Project Overview

In this project, we use SQL to explore and analyze retail transaction data.
- Understand customer behavior
- Track product performance
- Analyze sales trends
- Extract business insights from the data

## 🗃️ Dataset Description

The dataset consists of transaction records from a retail store. Below is the schema with column definitions:

| Column Name       | Description                                               |
|-------------------|-----------------------------------------------------------|
| `transactions_id` | Unique identifier for each transaction                    |
| `sale_date`       | Date of the sale (format: YYYY-MM-DD)                     |
| `sale_time`       | Time of the sale (format: HH:MM:SS)                       |
| `customer_id`     | Unique ID assigned to each customer                       |
| `gender`          | Gender of the customer (`Male` / `Female`)                |
| `age`             | Age of the customer                                       |
| `category`        | Product category (e.g., Electronics, Clothing)            |
| `quantiy`         | Quantity sold              |
| `price_per_unit`  | Price per unit of the product sold                        |
| `cogs`            | Cost of goods sold                                        |
| `total_sale`      | Total transaction value (`quantity * price_per_unit`)     |

## 🔍 Key Analysis Areas

This project answers questions such as:

- What are the total and average sales per product category?
- Which gender and age group contributes most to total revenue?
- What are the busiest times of day for sales?
- How are the top 5 customers based on the highest total sales?

## 🧰 Tools & Technologies

- **SQL** (MySQL – platform-independent)
- **SQL IDEs** (MySQL Workbench)
- **Excel**

## 🏁 How to Get Started

1. **Import the Dataset**  
   Loading the dataset into your SQL environment. Ensuring column names are clean and consistent.

2. **Check for Data Quality**  
   Handle null values, and outliers.

3. **Write and Run SQL Queries**  
   Begin exploring! Use SELECT, GROUP BY, WHERE, and JOINs as needed.

4. **Document Your Insights**  
    Summarising the findings 
