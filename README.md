# 🛒 Zepto Product Data Analysis Using SQL

## 📌 Project Overview

This project performs **data cleaning, exploration, and business analysis on Zepto product data using SQL**. The dataset contains information about product categories, prices, discounts, stock availability, and product weight.

The goal of this project is to extract **meaningful business insights from e-commerce product data** and demonstrate strong **SQL data analysis skills** including data exploration, cleaning, aggregation, and analytical queries.

---

## 🎯 Project Objectives

* Explore the **structure and quality of the dataset**
* Perform **data cleaning and preprocessing**
* Analyze **product pricing and discount patterns**
* Identify **high-value products and categories**
* Estimate **potential revenue across product categories**
* Generate **inventory insights for business decision-making**

---

## 📂 Dataset Description

The dataset includes product-level information from Zepto such as:

| Column                 | Description                        |
| ---------------------- | ---------------------------------- |
| sku_id                 | Unique product identifier          |
| category               | Product category                   |
| name                   | Product name                       |
| mrp                    | Maximum retail price               |
| discountPercent        | Discount percentage                |
| availableQuantity      | Quantity available in inventory    |
| discountedSellingPrice | Final selling price after discount |
| weightInGms            | Product weight                     |
| outOfStock             | Stock availability status          |
| quantity               | Product quantity                   |

---

## 🔎 Data Exploration

Initial exploration steps included:

* Counting total records
* Inspecting sample data
* Identifying missing values
* Listing unique product categories
* Analyzing stock availability
* Detecting duplicate product entries

These steps helped understand **data structure and potential quality issues**.

---

## 🧹 Data Cleaning

Data cleaning operations included:

* Removing products with **invalid price values**
* Converting **price units from paise to rupees**
* Filtering inconsistent records
* Ensuring data consistency for analysis

These steps improved **data reliability and accuracy**.

---

## 📊 Business Analysis Queries

Several analytical SQL queries were performed to extract insights:

### Key Analysis Performed

* Top **10 products with the highest discount**
* Products with **high MRP but out of stock**
* Estimated **revenue per product category**
* Products priced **above ₹500 with low discount**
* Categories offering **highest average discounts**
* **Best value products** based on price per gram
* Product grouping by **weight category**
* **Total inventory weight per category**

These analyses help understand **pricing strategy, inventory distribution, and product value**.

---

## 🛠️ SQL Concepts Used

This project demonstrates the use of important SQL concepts such as:

* Data Definition Language (DDL)
* Data Manipulation Language (DML)
* Filtering using `WHERE`
* Aggregation functions (`SUM`, `AVG`, `COUNT`)
* `GROUP BY` and `ORDER BY`
* `CASE` statements
* Data cleaning operations (`DELETE`, `UPDATE`)
* Sorting and ranking queries

---

## 📁 Project Structure

```text
Zepto-SQL-Data-Analysis/
│
├── Zepto_SQL_data_analysis.sql
└── README.md
```

---

## 📈 Key Insights

* Some products offer **very high discounts**, making them attractive to customers.
* Certain **high-value products are out of stock**, indicating potential lost sales.
* A few categories generate **significantly higher estimated revenue**.
* Price-per-gram analysis reveals **best-value products for customers**.

---

## ⭐ Skills Demonstrated

* SQL Data Analysis
* Data Cleaning
* Business Data Exploration
* Aggregation and Analytical Queries
* Inventory and Pricing Analysis

---

## 🚀 Future Improvements

* Create **SQL dashboards using Power BI or Tableau**
* Perform **trend analysis on sales data**
* Build **automated reporting queries**
* Integrate **SQL analysis with Python for deeper insights**

---

## 📌 Conclusion

This project demonstrates how SQL can be used to **analyze e-commerce product data, uncover pricing strategies, evaluate inventory distribution, and generate business insights**. It showcases practical SQL skills useful for **data analyst and business intelligence roles**.
