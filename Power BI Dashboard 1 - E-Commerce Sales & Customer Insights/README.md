# 📊 E-Commerce Sales & Customer Insights Dashboard

## 📌 Project Overview

This Power BI project analyzes e-commerce sales performance and customer behavior.
The dashboard provides actionable insights into sales trends,
customer segments, product performance, and regional sales distribution through interactive visualizations and KPIs.

---

## 📂 Dataset

The project uses three datasets:

### 🛒 Orders

* OrderID
* CustomerID
* ProductID
* Order Date
* Quantity
* Unit Price

### 👥 Customers

* CustomerID
* Customer Name
* City
* Gender

### 📦 Products

* ProductID
* Product Name
* Brand
* Category

### 📈 Dataset Size

* Orders: ~2,200 Records
* Customers: 300 Records
* Products: 100 Records

---

## 🧹 Data Cleaning & Transformation

Performed using Power Query:

✔ Removed unnecessary columns
✔ Corrected data types
✔ Handled missing values
✔ Merged lookup tables
✔ Created custom columns
✔ Renamed and reordered columns
✔ Calculated Sales column
✔ Applied data validation checks
✔ Standardized data formats

---

## 🔗 Data Model

### ⭐ Star Schema

Customers
      │
      │
Orders ───── Products
      │
      │
Date

### Relationships

* Customers → Orders (1:M)
* Products → Orders (1:M)
* Date → Orders (1:M)

---

## 📊 DAX Measures Created

* Total Sales
* Total Orders
* Total Customers
* Average Order Value (AOV)
* Customer Sales
* Customer Segment
* Category Wise Sales %

---

## 🎯 Key Performance Indicators (KPIs)

* 💰 Total Sales
* 📦 Total Orders
* 👥 Total Customers
* 📈 Average Order Value

---

## 🚀 Dashboard Features

### 📈 Sales Analysis

* Monthly Sales Trend
* Category Wise Sales Analysis
* Revenue Performance Tracking

### 📦 Product Analysis

* Top 4 Best-Selling Products
* Brand Performance Analysis

### 👥 Customer Analysis

* Customer Segmentation
* Customer Sales Distribution

### 🌍 Geographic Analysis

* State Wise Sales Performance
* Regional Sales Distribution

### 🎛 Interactive Filters

* Month
* Brand
* Category
* City

---

## 💡 Key Insights

* Electronics category generated the highest revenue.
* High-value customers contributed a significant share of total sales.
* A small group of products accounted for a large percentage of overall revenue.
* Sales performance varied across different regions and months.
* Interactive filters enable detailed business analysis.

---

## 🛠 Tools & Technologies Used

* Power BI
* Power Query
* DAX
* Data Modeling
* Data Cleaning & Transformation

---

## 🎯 Business Objective

The objective of this dashboard is to help businesses monitor sales performance, identify top-performing products and customer segments, and make data-driven decisions through interactive reporting and visual analytics.
