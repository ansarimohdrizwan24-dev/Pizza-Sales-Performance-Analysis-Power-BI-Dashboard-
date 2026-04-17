# 🍕 Pizza Sales Performance Analysis (Power BI Dashboard)

## 🎯 Objective

The objective of this project is to perform end-to-end analysis of pizza sales data by applying data cleaning, transformation,and visualization techniques.
The project aims to identify revenue patterns, peak ordering times, and customer behavior to help businesses optimize sales strategy and improve decision making using Power BI.

## 📊 Project Overview

This project presents an interactive Power BI dashboard to analyze pizza sales data. It helps in understanding revenue trends, customer behavior, and product performance.

## 🧹 Data Cleaning 

- Removed unnecessary columns such as `pizza_id`, `ingredients`, and `order_details_id` to reduce data redundancy and improve performance
- Handled missing and inconsistent values to ensure data accuracy
- Converted data types (date and numeric) for proper analysis

## 🔄 Data Transformation
- Extracted **Month Name** from `order_date` for monthly trend analysis
- Extracted **Day Name** from `order_date` to analyze weekday patterns
- Extracted **Hour** from `order_time` to identify peak order times
- Created a new column **Day Type (Weekday/Weekend)** from Day Name for customer behavior analysis
- Used **Power Query** for data transformation

## 🧮 DAX Measures & Calculations

- Created key measures using DAX:
  - **Total Revenue** – sum of total sales amount
  - **Total Pizzas Sold** – total quantity of pizzas sold
  - **Total Orders** – count of total orders

- Created calculated measure:
  - **Average Order Value (AOV)** = Total Revenue / Total Orders

- Used DAX functions to build dynamic and interactive KPIs

## 📊 Feature Engineering
- Created key performance indicators (KPIs):
  - Total Revenue  
  - Total Orders  
  - Total Pizzas Sold  
  - Average Order Value 


## Key Metrics

-Total Revenue: 818K+
-Total Orders: 21K+
-Total Pizzas Sold: 50K+
-Average Order Value: 38

## Dashboard Features

🔹 Executive Summary

-Revenue by Month
-Revenue by Category
-Revenue by Size
-Orders by Hour

🔹 Product Performance

- Top 10 Pizzas by Revenue
- Top 10 Pizzas by Quantity Sold
- Detailed performance table

🔹 Time & Customer Insights
- Revenue by Day
- Weekday vs Weekend Analysis
- Order Density by Time

## Tools Used

- Power BI
- Data Analysis
- Data Visualization

## Dashboard Preview

<img width="1305" height="784" alt="image" src="https://github.com/user-attachments/assets/4f947bce-2ca3-43ad-8b5a-cf368a1b12cb" />

<img width="1303" height="798" alt="image" src="https://github.com/user-attachments/assets/f9d5b826-12cf-4029-a549-1933040f1a7f" />

<img width="1294" height="791" alt="image" src="https://github.com/user-attachments/assets/fde433b0-a048-446f-bab9-0cfec6dfa362" />


## 📌 Conclusion

This dashboard provides valuable business insights that help in identifying top-selling products, peak sales hours, and customer purchasing patterns, enabling data-driven decision making.


