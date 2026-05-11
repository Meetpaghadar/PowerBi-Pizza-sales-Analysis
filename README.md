# 🍕 Pizza Sales Analysis Dashboard

An end-to-end Business Intelligence project focused on analyzing pizza sales data to uncover revenue trends, customer ordering behavior, top-performing products, and operational insights using SQL, Excel, Power BI, and Tableau.

---

# 📷 Preview

## Excel Dashboard
<img width="1002" height="602" alt="Excel Dashboard" src="https://github.com/user-attachments/assets/70001849-0a8c-4285-b134-5d2e5cee61b7" />

## Power BI Dashboard
<img width="1159" height="653" alt="Power BI Dashboard" src="https://github.com/user-attachments/assets/567278fb-cf18-420b-bd90-3e3e00458451" />

## Sales Insights Dashboard
<img width="1155" height="640" alt="Sales Insights Dashboard" src="https://github.com/user-attachments/assets/3ce42fc0-d576-4f35-97f9-79c1647c1034" />

---

# 📌 Project Overview

The goal of this project was to analyze historical pizza sales data and transform raw transactional records into meaningful business insights that support data-driven decision-making.

The analysis focuses on identifying:
- Revenue performance
- Customer ordering patterns
- Peak sales periods
- Best & worst-selling pizzas
- Sales contribution by category and size
- Order behavior trends

The project follows a complete analytics workflow starting from data acquisition in SQL Server to dashboard creation in Excel, Power BI, and Tableau.

---

# 🚀 Key Business Questions Solved

✔ Which pizza category generates the highest revenue?  
✔ What are the peak order hours and busiest days?  
✔ Which pizzas are top-selling and underperforming?  
✔ How much revenue does each pizza size contribute?  
✔ What is the average order value and average pizzas per order?  
✔ How do monthly and weekly sales trends behave?  

---

# 🛠 Tech Stack

| Tool | Purpose |
|------|----------|
| SQL Server | Data querying & KPI calculations |
| Excel | Pivot analysis & dashboard creation |
| Power BI | Interactive business dashboard |
| Tableau | Data visualization |
| DAX | Calculated measures in Power BI |
| Power Query | Data transformation |

---

# 📂 Dataset

- **Dataset:** Pizza Sales Data 2015
- **Source:** Kaggle
- **Data Includes:** Orders, Revenue, Pizza Categories, Sizes, Quantities, Dates & Time

---

# 📊 KPIs Analyzed

| KPI | Description |
|------|-------------|
| Total Revenue | Total sales generated |
| Total Orders | Number of orders placed |
| Total Pizzas Sold | Quantity of pizzas sold |
| Average Order Value | Revenue per order |
| Average Pizzas per Order | Average items ordered |
| Sales by Category | Revenue distribution by pizza category |
| Sales by Size | Contribution by pizza size |

---

# 📈 Dashboard Features

## 📅 Sales Trend Analysis
- Daily order trends
- Weekly sales patterns
- Monthly revenue growth
- Hourly peak order analysis

## 🍕 Product Performance
- Best-selling pizzas
- Worst-selling pizzas
- Category-wise revenue contribution
- Size-wise demand analysis

## 📊 Interactive Visualizations
- Dynamic filters
- KPI cards
- Pie charts
- Bar charts
- Trend lines
- Comparative analysis dashboards

---

# 🧠 SQL Analysis Performed

### Total Revenue
```sql
SELECT SUM(total_price) AS Total_Revenue
FROM pizza_sales;
```

### Total Orders
```sql
SELECT COUNT(DISTINCT order_id) AS Total_Orders
FROM pizza_sales;
```

### Average Order Value
```sql
SELECT SUM(total_price) / COUNT(DISTINCT order_id) AS Avg_Order_Value
FROM pizza_sales;
```

### Additional SQL Concepts Used
- Aggregate Functions
- GROUP BY
- ORDER BY
- Date Functions
- CTEs
- Joins
- KPI Calculations

---

# 📌 Power BI Dashboard Highlights

The Power BI dashboard was designed to provide business stakeholders with a clear and interactive view of sales performance.

### Features:
- Dynamic slicers
- Interactive drill-down analysis
- DAX measures for KPI tracking
- Category and size filtering
- Time-series analysis
- Executive-level dashboard design

---

# 🔍 Key Insights Discovered

- Peak sales occurred during weekends and evening hours.
- Classic pizzas contributed the highest share of total sales.
- Large-size pizzas generated the most revenue.
- Certain pizza categories consistently underperformed, indicating opportunities for menu optimization.
- Customer ordering behavior showed strong seasonal and hourly trends.

---

# 📁 Project Structure

```bash
Pizza-Sales-Analysis/
│
├── Dataset/
├── SQL Queries/
├── Excel Dashboard/
├── Power BI Dashboard/
├── Tableau Dashboard/
├── Images/
└── README.md
```

---

# 🎯 Business Impact

This project demonstrates how raw transactional sales data can be transformed into actionable business insights that help:
- Improve sales strategy
- Optimize inventory planning
- Identify high-performing products
- Understand customer behavior
- Support data-driven decision-making

---
