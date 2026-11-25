# 🍕 Pizza Sales Performance & Revenue Analytics Dashboard

## 📊 Dashboard Preview
![Pizza Sales Dashboard](images/dashboard-overview.png)

## 🎯 Business Objective
An end-to-end Business Intelligence dashboard built in **Power BI Desktop** to evaluate annual restaurant sales performance, track customer ordering behavior, and identify top- and bottom-performing menu items to support inventory planning and promotional strategy.

## 📈 Key Performance Indicators (KPIs)
* **Total Revenue:** $801.29K
* **Total Pizzas Sold:** 48.5K+
* **Total Orders:** 21K+
* **Average Order Value (AOV):** Dynamically calculated via DAX to track average customer spend
* **Average Pizzas per Order:** Measures multi-item order volume

## 💡 Key Business Insights
* **Top-Performing Category:** The **Classic** category generates the highest share of both total revenue and order volume.
* **Size Preference:** **Large** pizzas contribute the largest percentage of total sales, serving as the primary revenue driver.
* **Peak Ordering Windows:** Sales volume peaks on weekend evenings (Fridays and Saturdays) and during the daily lunch rush (12:00 PM – 1:00 PM).
* **Menu Optimization:** Highlights the top 5 best-selling pizzas for combo promotions and the bottom 5 underperforming pizzas for pricing or recipe review.

## 🛠️ Tools & Technical Implementation
* **Power Query (ETL):** Cleaned raw transactional data, handled data type conversions, and extracted day-of-week and hourly columns for time-intelligence analysis.
* **DAX (Data Analysis Expressions):** Built custom measures for Total Revenue, Average Order Value, Total Pizzas Sold, and `% of Sales` by category and size.
* **Interactive Visuals:** Configured dynamic slicers for **Date Range** and **Pizza Category**, custom KPI cards, and conditional formatting for executive-ready reporting.

## 📂 Repository Contents
* `Pizza_Sales_Dashboard.pbix` — Complete Power BI report file with data model, Power Query steps, and DAX measures.
* `pizza_sales.csv` — Raw dataset used for analysis.
* `images/` — High-resolution screenshots of the dashboard pages.

## 🚀 How to View This Project
1. Click on the `.pbix` file in the repository above and select **Download raw file**.
2. Open the file in **Power BI Desktop** (free download from Microsoft) to explore the interactive charts, slicers, and DAX formulas.
