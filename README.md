# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into customer preferences, spending patterns, subscription behavior, and product performance.

The analysis combines:

* Python for data cleaning and preprocessing
* PostgreSQL for business analysis queries
* Power BI for interactive dashboard visualization

The goal is to help businesses improve:

* Customer engagement
* Marketing strategies
* Product positioning
* Revenue optimization
* Customer loyalty programs

---

## Business Problem

A retail company wanted to understand how customer demographics, discounts, subscriptions, reviews, and shopping behavior affect purchasing decisions and long-term loyalty.

Main business question:

> “How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

---

## Dataset Information

* Total Records: 3,900
* Features: 18
* Includes:

  * Customer demographics
  * Purchase behavior
  * Product categories
  * Discounts & promo usage
  * Subscription status
  * Shipping preferences
  * Product reviews

---

## Tools & Technologies Used

### Python

* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

### SQL

* PostgreSQL

### Visualization

* Power BI

### Version Control

* Git & GitHub

---

## Project Workflow

### 1. Data Cleaning & Preparation (Python)

* Handled missing values
* Standardized column names
* Feature engineering
* Age group segmentation
* Data consistency checks
* Exported cleaned data to PostgreSQL

### 2. Business Analysis (SQL)

Performed SQL queries to analyze:

* Revenue by gender
* High-spending discount users
* Top-rated products
* Customer segmentation
* Subscription behavior
* Revenue by age group
* Shipping type comparison

### 3. Dashboard Creation (Power BI)

Built an interactive dashboard to visualize:

* Revenue trends
* Customer segmentation
* Sales by category
* Subscription insights
* Revenue by age group
* Average ratings

---

## Key Insights

* Male customers generated higher total revenue.
* Loyal customers formed the majority of the customer base.
* Express shipping users had higher average purchase amounts.
* Clothing category generated the highest sales.
* Young adults contributed the highest revenue.
* Some products showed strong dependency on discounts.

---

## Business Recommendations

* Improve subscription benefits to increase retention.
* Reward repeat customers through loyalty programs.
* Promote top-rated products in marketing campaigns.
* Optimize discount strategies to maintain profitability.
* Focus targeted marketing on high-value customer groups.

---

## Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── customer_shopping_behavior.csv
├── Customer Shopping Behavior Analysis.pdf
├── Business Problem Document.pdf
├── README.md
└── Customer-Shopping-Behavior-Analysis.pptx
```

---

## Dashboard Preview

(Add screenshots here from your Power BI dashboard)

---

## How to Run the Project

### Python Analysis

```bash
pip install pandas numpy matplotlib
```

Run the Jupyter notebook:

```bash
jupyter notebook
```

### SQL Queries

Import the cleaned dataset into PostgreSQL and execute the SQL queries provided in:

```bash
customer_behavior_sql_queries.sql
```

### Power BI Dashboard

Open:

```bash
customer_behavior_dashboard.pbix
```

using Microsoft Power BI Desktop.

---

## Future Improvements

* Add machine learning prediction models
* Build customer churn prediction
* Deploy dashboard online
* Automate ETL pipeline
* Add real-time analytics

---

## Author

### Suyog Taware

* Aspiring Data Analyst
* Skilled in Python, SQL, Power BI, and Data Visualization

GitHub:
https://github.com/SuyogTaware29
