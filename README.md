# 🛍️ Retail Sales Analysis (SQL Project)

Welcome to the **Retail Sales Analysis** SQL project!  
This project is designed to showcase practical SQL skills by analyzing retail transaction data to uncover sales trends, customer behavior, and business insights.

---

## 📁 Project Overview

In this project, we use SQL to explore and analyze retail transaction data. It is ideal for beginner to intermediate learners who want to:

- Strengthen SQL querying skills
- Practice data cleaning and aggregation
- Develop insights from structured business data
- Build portfolio-ready analytics projects

---

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
| `quantiy`         | Quantity sold *(typo; should be `quantity`)*              |
| `price_per_unit`  | Price per unit of the product sold                        |
| `cogs`            | Cost of goods sold                                        |
| `total_sale`      | Total transaction value (`quantity * price_per_unit`)     |

> 📝 **Note**: You may want to rename `quantiy` to `quantity` during the cleaning process.

---

## 🔍 Key Analysis Areas

This project answers questions such as:

- What are the total and average sales per product category?
- Which gender and age group contributes most to total revenue?
- What are the busiest times of day for sales?
- How does profit vary across categories?
- What are the high-performing vs. underperforming products?

---

## 🧰 Tools & Technologies

- **SQL** (MySQL / PostgreSQL / SQLite – platform-independent)
- SQL IDEs (e.g., DBeaver, pgAdmin, MySQL Workbench)
- **Optional**: Excel or Power BI for visualizing query results

---

## 🚀 How to Use

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/<your-username>/retail-sales-sql-project.git
   cd retail-sales-sql-project

2. **Import Dataset**
Load the dataset (CSV or SQL dump) into your SQL environment.

3. **Explore SQL Queries**
Navigate to the queries/ folder and run the SQL scripts to explore the data.

4. **Clean and Transform**
Rename columns, handle typos, check for NULLs, and prepare the data for analysis.

5. **Analyze and Document**
Use SQL to extract insights, then document them in the insights/ folder.
