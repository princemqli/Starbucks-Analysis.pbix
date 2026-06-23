<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/d/d3/Starbucks_Corporation_Logo_2011.svg" width="220">
</p>

<h1 align="center">☕ Starbucks Sales Analysis Dashboard</h1>

<p align="center">
A Professional Power BI Dashboard for Sales Performance, Product Analytics, Customer Insights, and Business Intelligence
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow">
  <img src="https://img.shields.io/badge/DAX-Analytics-blue">
  <img src="https://img.shields.io/badge/Power%20Query-ETL-green">
  <img src="https://img.shields.io/badge/Business%20Intelligence-Reporting-success">
</p>

---

# 📌 Project Overview

The Starbucks Sales Analysis Dashboard is a comprehensive Business Intelligence solution developed using Power BI. This project transforms raw sales data into actionable business insights through interactive visualizations, KPI tracking, and advanced analytics.

The dashboard enables decision-makers to monitor business performance, identify revenue trends, evaluate product performance, and understand customer purchasing behavior.

---

# 🎯 Business Objectives

- Analyze overall sales performance.
- Track revenue growth and trends.
- Identify top-performing products and categories.
- Understand customer purchasing behavior.
- Monitor key business KPIs.
- Support strategic decision-making.

---

# 📂 Dataset Information

The dataset contains Starbucks transactional sales records including:

- Transaction Date
- Product Name
- Product Category
- Quantity Sold
- Sales Revenue
- Store Information
- Order Details

The data was cleaned, transformed, and modeled using Power Query and Power BI Data Modeling techniques.

---

# 🏗 Data Model

This project follows a Star Schema Data Model for optimal reporting performance.

### Fact Table
- Sales Fact Table

### Dimension Tables
- Date Dimension
- Product Dimension
- Category Dimension
- Store Dimension

### Relationships
- One-to-Many Relationships
- Optimized Data Modeling Structure

---

# 🛠 Tools & Technologies

### Business Intelligence
- Power BI Desktop

### Data Transformation
- Power Query

### Data Modeling
- Star Schema

### Analytics
- DAX (Data Analysis Expressions)

### Reporting
- Interactive Dashboards

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Description |
|------|------------|
| Total Sales | Total Revenue Generated |
| Total Orders | Number of Transactions |
| Total Quantity Sold | Products Sold |
| Average Order Value | Revenue Per Order |
| Sales Growth % | Revenue Growth |
| MTD Sales | Month-to-Date Sales |
| YTD Sales | Year-to-Date Sales |

---

# ⚡ DAX Measures Used

```DAX
Total Sales =
SUM(Sales[Revenue])

Total Orders =
DISTINCTCOUNT(Sales[Transaction_ID])

Total Quantity =
SUM(Sales[Quantity])

Average Order Value =
DIVIDE([Total Sales],[Total Orders])

YTD Sales =
TOTALYTD([Total Sales],'Date'[Date])

MTD Sales =
TOTALMTD([Total Sales],'Date'[Date])

Sales Growth % =
DIVIDE(
    [Total Sales] - [Last Year Sales],
    [Last Year Sales]
)

Running Total Sales =
CALCULATE(
    [Total Sales],
    FILTER(
        ALL('Date'),
        'Date'[Date] <= MAX('Date'[Date])
    )
)
```

---

# 📈 Dashboard Features

## Executive Summary

- Total Sales Overview
- Revenue Tracking
- Business Performance KPIs

## Sales Analysis

- Daily Sales Trend
- Monthly Revenue Trend
- Peak Sales Period Analysis
- Revenue Comparison

## Product Performance

- Top Selling Products
- Revenue by Product Category
- Product Ranking
- Category Contribution Analysis

## Customer Insights

- Customer Purchase Patterns
- Order Distribution
- Buying Behavior Analysis

## Interactive Reporting

- Dynamic Filters
- Slicers
- Drill Through Pages
- Cross Filtering

---

# 📊 Visualizations Used

### KPI Cards
- Total Sales
- Total Orders
- Total Quantity Sold
- Average Order Value

### Charts
- Line Chart
- Bar Chart
- Clustered Column Chart
- Donut Chart
- Area Chart

### Tables
- Matrix Table
- Detailed Transaction Table

### Filters
- Date Slicer
- Product Filter
- Category Filter

---

# 🔄 Power Query Transformations

The following transformations were performed:

- Data Type Conversion
- Null Value Handling
- Duplicate Removal
- Date Formatting
- Column Renaming
- Data Cleaning
- Custom Column Creation

---

# 💡 Business Insights

### Revenue Insights

- Coffee products generate the highest revenue contribution.
- Sales peak during morning and evening business hours.
- Revenue shows strong seasonal patterns.

### Product Insights

- Top-performing products contribute significantly to overall revenue.
- Certain categories consistently outperform others.

### Customer Insights

- Customer purchasing behavior impacts revenue growth.
- Repeat purchases contribute to business performance.

### Operational Insights

- Product demand trends can support inventory planning.
- Sales analysis helps optimize business strategies.

---

# 🚀 Business Impact

This dashboard helps businesses:

✔ Monitor performance in real time

✔ Identify revenue opportunities

✔ Improve inventory management

✔ Understand customer preferences

✔ Optimize product strategies

✔ Support data-driven decision making

---

# 📷 Dashboard Preview

## Executive Dashboard
(Add Screenshot Here)

## Sales Analysis Dashboard
(Add Screenshot Here)

## Product Performance Dashboard
(Add Screenshot Here)

## Customer Insights Dashboard
(Add Screenshot Here)

---

# 🔮 Future Enhancements

- Sales Forecasting
- Predictive Analytics
- Customer Segmentation
- Regional Performance Analysis
- Advanced KPI Tracking

---

# 👨‍💻 Author

## Prince

BCA Student | Data Science Enthusiast | Power BI Developer

### Skills
- Power BI
- SQL
- Python
- Data Analytics
- Data Visualization
- Business Intelligence

---

# ⭐ Project Highlights

✅ End-to-End Power BI Project

✅ Data Cleaning using Power Query

✅ Star Schema Data Modeling

✅ Advanced DAX Measures

✅ Interactive Dashboard Design

✅ Business KPI Tracking

✅ Data-Driven Insights

✅ Professional Reporting Solution

---

## 📬 Connect With Me

- LinkedIn: Add Your LinkedIn Profile
- GitHub: Add Your GitHub Profile

---

### ⭐ If you found this project useful, consider giving it a star.
### ☕ Thank you for visiting this repository.
