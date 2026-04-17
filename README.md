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

## Charts and Insights

1. Executive Summary Dashboard
   Charts Used + Explanation

   1️⃣ KPI Cards (Top Metrics)
      What it shows:
      - Total Revenue
      - Average Order Value
      - Total Pizzas Sold
      - Total Orders 

   2️⃣ Total Revenue by Month
       Chart Type: Line Chart
       What it shows:
        - Monthly trend of total revenue over time
   
   3️⃣ Total Revenue by Category
      Chart Type: Donut Chart
      What it shows:
       - Contribution of each pizza category (Classic, Supreme, etc.)
  
   4️⃣ Total Revenue by Size
      Chart Type: Donut Chart
      What it shows:
       - Revenue distribution by pizza size (S, M, L, XL)
  
   5️⃣ Total Orders by Hour
      Chart Type: Bar Chart / Column Chart
      What it shows:
       - Number of orders placed in each hour of the day

   6️⃣ Total Orders by Day
      Chart Type: Bar Chart
      What it shows:
       - Orders distribution across days (Mon–Sun)
   
2. Product Performance Dashboard

   1️⃣ Top 10 Pizzas by Revenue
      Chart Type: Horizontal Bar Chart
      What it shows:
       - Top 10 pizzas generating highest revenue

   2️⃣ Top 10 Pizzas by Quantity Sold
      Chart Type: Horizontal Bar Chart
      What it shows:
       - Pizzas sold in highest quantity

   3️⃣ Total Sales by Category
      Chart Type: Bar Chart / Column Chart
      What it shows:
       - Sales comparison across pizza categories

   4️⃣ Detailed Product Table
      Chart Type: Table / Matrix
      What it shows:
      👉 Each pizza with:
         - Revenue
         - Quantity sold
         - Orders

   5️⃣ Category Filters / Slicers
      Chart Type: Slicer
      What it shows:
       - Filters data by category, size, etc.

### Important Insight(Product Performance)
  👉 Difference between:
     - Top Revenue Pizza ≠ Top Quantity Pizza
  👉 Means:
     - Some pizzas are expensive (high revenue)
     - Some are popular (high quantity)

3. Time & Customer Insights Dashboard

   1️⃣ Total Revenue by Day
      Chart Type: Bar Chart
      What it shows:
       - Revenue generated on each day (Mon–Sun)

   2️⃣ Weekday vs Weekend Sales
      Chart Type: Bar Chart / Column Chart
      What it shows:
      - Comparison between weekday and weekend sales

   3️⃣ Orders by Hour (Time Analysis)
      Chart Type: Bar Chart
      What it shows:
      - Number of orders at each hour

   4️⃣ Sales Trend Over Time
      Chart Type: Line Chart
      What it shows:
      - Revenue trend over time (daily/monthly)

###Key Business Insights(Time & Customer Insights)

      From this dashboard you can say:
        - Peak sales happen during specific hours (like evening)
        - Weekends usually have higher sales than weekdays
        - Some days consistently perform better

##📊 Project Summary

This project analyzes pizza sales data using Power BI to extract meaningful business insights. It includes data cleaning, transformation, and visualization to understand revenue trends, customer behavior, and product performance. The dashboards highlight key metrics, top-selling pizzas, peak ordering hours, and sales patterns across time, helping in data-driven decision making.

## 📌 Conclusion

This dashboard provides valuable business insights that help in identifying top-selling products, peak sales hours, and customer purchasing patterns, enabling data-driven decision making.


