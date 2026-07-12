#  Zepto SQL Data Analysis

## Overview

This project demonstrates SQL-based analysis of a real-world e-commerce inventory dataset using PostgreSQL. The workflow includes importing raw inventory data, performing exploratory data analysis (EDA), cleaning inconsistent records, and answering business questions through SQL queries.

The project showcases practical SQL techniques used in data analytics to extract meaningful insights from retail inventory data.

---

## Dataset

The dataset contains product inventory information, including:

- Product Name
- Brand
- Category
- MRP
- Selling Price
- Discount Percentage
- Available Quantity
- Stock Status

---

## Tools & Technologies

- PostgreSQL
- SQL
- pgAdmin

---

## Project Workflow

### Database Setup
- Created database and table schema
- Imported CSV dataset into PostgreSQL

### Data Exploration
- Examined dataset structure
- Checked missing values
- Identified duplicate records
- Explored product categories and brands

### Data Cleaning
- Removed invalid records
- Standardized pricing values
- Handled missing data
- Prepared data for analysis

### Business Analysis

Performed SQL analysis to answer questions such as:

- Which categories have the most products?
- Which products offer the highest discounts?
- What is the average selling price by category?
- Which brands have the highest inventory value?
- Which products are out of stock?
- Which categories contribute the highest potential revenue?

---

## SQL Concepts Used

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- Aggregate Functions
- CASE Statements
- Common Table Expressions (CTEs)
- Window Functions
- Subqueries
- String Functions

---

## Repository Structure

```text
.
├── README.md
├── Zepto_SQL_data_analysis.sql
└── zepto_v2.csv
```

---

## Key Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Insight Generation
- Retail Inventory Analysis
- PostgreSQL

---

## Future Improvements

- Build an interactive Power BI dashboard.
- Optimize query performance using indexes.
- Create SQL views for reporting.
- Automate data loading using Python.
