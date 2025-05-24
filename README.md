# 🍕 Pizza Sales Analysis

## 📊 Project Overview

This project analyzes a pizza restaurant's sales data to uncover business insights and help guide decision-making. Using **SQL** for data querying and **Excel** for visualization, we explore key performance indicators (KPIs), customer behavior, and product performance to identify trends, opportunities, and areas for improvement.

## Repository Structure

 **Pizza-Sales-Analysis/**

  - Problem Statement/
     - [Problem Statement](Problem_Statement.pptx)  
  - data/
     - [pizza_sales_data](Pizza_Sales_Analysis.xlsx)
  - queries/
     - [sql_queries](PIZZA_SALES_SQL_QUERIES.docx)
  - visuals/
     - [Pizza_Sales_Screenshot](Pizza_Sales_Dashboard.PNG)
  - Video/
     - [Video Pizaa_Sales](Video_Pizaa_Sales.rar)
  - README.md

## 🎯 Problem Statement

We aim to analyze key indicators from our pizza sales dataset to evaluate business performance and visualize critical trends. The objectives include:

- Understanding total revenue and average customer spend.
- Identifying peak sales hours and high-performing days.
- Analyzing performance by pizza category and size.
- Recognizing best and worst-selling pizzas.

## ✅ KPI Requirements

| KPI | Description |
|-----|-------------|
| **Total Revenue** | Total amount of money earned from pizza sales. |
| **Average Order Value** | Total revenue divided by total number of orders. |
| **Total Pizzas Sold** | Total number of pizza units sold. |
| **Total Orders** | Total number of customer orders placed. |
| **Average Pizzas Per Order** | Total pizzas sold divided by the total number of orders. |

> **KPIs Results (from dashboard):**  
> • Total Revenue: **$208,370**  
> • Avg Order Value: **$38.41**  
> • Total Pizzas Sold: **12,586**  
> • Total Orders: **5,425**  
> • Avg Pizzas Per Order: **2.32**

## 📈 Visualizations

### 1. Hourly Trend for Total Orders
A **stacked bar chart** showing hourly order volume helps identify sales spikes.  
**Insight:** Orders peak during lunch hours (12–1 PM) and evening hours (5–8 PM), aligning with typical meal times.

### 2. Weekly Trend for Total Orders
A **line chart** illustrating order volumes by weekday.  
**Insight:** Weekends (Friday and Saturday) show the highest order volume, while Sunday has the lowest.

### 3. % of Sales by Pizza Category
A **pie chart** breaking down sales by pizza type (e.g., Classic, Supreme).  
**Insight:**  
- **Classic** pizzas lead with 27.01% of total sales.  
- Followed by **Veggie** (25.94%), **Supreme** (23.38%), and **Chicken** (23.67%).

### 4. % of Sales by Pizza Size
A **pie chart** of sales share by pizza size.  
**Insight:**  
- **Large** pizzas account for the majority at 45.63%.  
- Followed by **XLarge** (31.12%) and **Medium** (21.03%).

### 5. Total Pizzas Sold by Pizza Category
A **funnel chart** comparing volume sold per category.  
**Insight:**  
- **Classic** pizzas dominate in total units sold (3,776), followed by **Supreme**, **Veggie**, and **Chicken**.

### 6. Top 5 Best Sellers (Revenue, Quantity, Orders)
A **bar chart** featuring pizzas with the highest:
- Sales revenue
- Total quantity sold
- Number of orders

**Insight:**  
- Top sellers:  
  1. **Barbecue Chicken Pizza** (634 sold)  
  2. **Classic Deluxe Pizza** (631)  
  3. **Hawaiian Pizza** (606)  
  4. **California Chicken Pizza** (597)  
  5. **Thai Chicken Pizza** (583)

### 7. Bottom 5 Worst Sellers (Revenue, Quantity, Orders)
A **bar chart** of least popular pizzas by revenue, quantity, and orders.  
**Insight:**  
- Bottom sellers include:  
  - **Brie Carre Pizza** (118 sold)  
  - **Chicken Alfredo Pizza**  
  - **Spinach Pesto Pizza**  
  - **Italian Vegetables Pizza**  
  - **Mediterranean Pizza**

## 💡 Business Insights

- **Classic** and **Chicken** pizzas are top contributors in both sales and revenue.
- **Large size** is the most popular and profitable.
- **Fridays and Saturdays** show the highest order activity—ideal for promotional campaigns.
- Sales spike during **lunch (12–1 PM)** and **dinner (5–8 PM)**.
- **Brie Carre Pizza** consistently underperforms; consider removal or marketing support.

## 🛠 Tools Used

- **SQL:** Data extraction and KPI calculations.
- **Excel:** Dashboard creation and visualizations.
- **Power Query / Pivot Tables:** Data aggregation and cleaning (if applicable).


