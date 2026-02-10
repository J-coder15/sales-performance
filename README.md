# sales-performance
# 📊 Sales Performance Analysis (2018–2024) | Power BI

This repository contains a **Power BI data visualization project** that analyzes **sales performance from 2018 to 2024** using data from two relational tables: **Orders** and **Products**.  
The dashboard provides insights into **sales trends, product performance, and revenue growth over time**.

---

## 🔍 Project Objective
The objective of this project is to:
- Analyze **yearly and monthly sales performance** from 2018–2024
- Understand how **products contribute to total sales**
- Identify **sales trends and growth patterns**
- Support **business decision-making** through interactive dashboards

---

## 🗂️ Data Model
The analysis is built on a **star-schema-like structure** with two tables:

### 📦 Orders Table
Contains transactional sales data:
- Order ID  
- Order Date  
- Product ID (Foreign Key)  
- Sales  
- Quantity  
- Discount  
- Profit  

### 🛍️ Products Table
Contains product-level information:
- Product ID (Primary Key)  
- Product Name  
- Category  
- Sub-Category  

The tables are connected via **Product ID**, enabling detailed product-level analysis.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Data modeling & visualization  
- **Power Query** – Data cleaning and transformation  
- **DAX** – Measures, KPIs, and time-intelligence calculations  
- **Excel / CSV** – Data source  

---

## 📈 Key Metrics & KPIs
- Total Sales  
- Total Profit  
- Profit Margin  
- Quantity Sold  
- Year-over-Year (YoY) Sales Growth  
- Sales Trend (2018–2024)  

---

## 💡 Key Insights
- Sales show **clear growth patterns** across the 2018–2024 period.
- Certain products and categories contribute **disproportionately to revenue**.
- Discounting increases sales volume but can **negatively impact profit margins**.
- Seasonal trends influence sales performance in specific years.

---

## 📊 Dashboard Features
- Year and date-based slicers (2018–2024)
- Product and category filters
- KPI cards for high-level performance tracking
- Trend analysis using line and bar charts
- Drill-down analysis by product and time

---

## 🖼️ Dashboard Preview
> *(Insert Power BI dashboard screenshot here)*

![Sales Performance Dashboard](./assets/sales_performance_dashboard.png)

---

## 📂 Repository Structure
