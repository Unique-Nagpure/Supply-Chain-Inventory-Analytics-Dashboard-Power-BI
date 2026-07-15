📦 Supply Chain & Inventory Analytics Dashboard | Power BI

## 📌 Project Overview

This project demonstrates an end-to-end **Supply Chain & Inventory Analytics Dashboard** developed using **Power BI**. The objective is to analyze inventory movement, warehouse utilization, supplier performance, and overall business operations through interactive dashboards and meaningful KPIs.

The project follows a **Star Schema Data Model**, consisting of multiple dimension tables and a large fact table, making it suitable for demonstrating real-world Business Intelligence and Data Engineering concepts.

---

## 🎯 Business Objective

The dashboard helps business users answer questions such as:

* Which warehouses currently hold the highest inventory?
* How much inventory has been received and sold over time?
* Which suppliers are performing efficiently?
* What is the current stock availability across warehouses?
* How are sales and profit trending over time?
* What is the overall inventory turnover?

---

## 🏗 Data Model

The solution follows a **Star Schema**.

### Dimension Tables

* **DimProduct** – Product details including category, brand, pricing, and reorder level.
* **DimSupplier** – Supplier information including ratings and lead time.
* **DimWarehouse** – Warehouse details and storage capacity.
* **DimDate** – Calendar table for time intelligence.
* **DimLocation** – Regional and geographical information.

### Fact Table

* **FactInventory**

  * Inventory Transactions
  * Quantity Received
  * Quantity Sold
  * Current Stock
  * Purchase Cost
  * Selling Price
  * Delivery Days
  * Order Status

---

## 📊 Dataset Size

| Table         |   Records |
| ------------- | --------: |
| DimProduct    |     8,000 |
| DimSupplier   |     3,000 |
| DimWarehouse  |       500 |
| DimLocation   |       250 |
| DimDate       |     2,557 |
| FactInventory | 3,000,000 |

---

## 📈 Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of business performance using KPI cards and trend analysis.

**KPIs**

* Total Sales
* Gross Profit
* Total Transactions
* Current Stock
* Product Count
* Supplier Count
* Warehouse Count
* Inventory Turnover

**Visuals**

* Monthly Sales Trend
* Monthly Profit Trend
* Order Status Distribution
* Sales by Product Category
* Sales by Brand
* Interactive Slicers

---

### 2. Inventory & Warehouse Analysis

Focuses on inventory movement and warehouse performance.

**KPIs**

* Quantity Received
* Quantity Sold
* Current Stock
* Average Inventory

**Visuals**

* Warehouse Stock Analysis
* Quantity Received vs Quantity Sold
* Inventory Matrix
* Warehouse Capacity Analysis
* Product Inventory Details

---

### 3. Supplier Performance

Analyzes supplier efficiency and operational performance.

**KPIs**

* Supplier Count
* Average Delivery Days
* Delivered Orders
* Delayed Orders

**Visuals**

* Supplier Performance
* Supplier Rating vs Delivery Days
* Order Status Analysis
* Top Suppliers

---

## 📊 Key DAX Measures

* Total Sales
* Gross Profit
* Profit Margin %
* Total Transactions
* Quantity Received
* Quantity Sold
* Current Stock
* Average Inventory
* Inventory Turnover
* Average Delivery Days
* Delivered Orders
* Pending Orders
* Delayed Orders
* On-Time Delivery %
* Sales YTD
* Sales MTD
* Sales QTD
* Previous Year Sales
* YoY Growth %

---

## 🛠 Tools & Technologies

* Power BI Desktop
* DAX
* Power Query
* Star Schema Data Modeling
* Data Visualization
* CSV Dataset
* Git & GitHub

---

## 📌 Features

* Interactive multi-page dashboard
* Star schema data model
* Large-scale dataset with **3 million inventory transactions**
* Drill-down and cross-filtering
* KPI-driven reporting
* Time intelligence analysis
* Supplier and warehouse performance monitoring
* Inventory trend analysis

---

## 🚀 Skills Demonstrated

* Data Modeling
* Power BI Dashboard Development
* DAX Measures
* Business Intelligence Reporting
* Supply Chain Analytics
* Inventory Analytics
* Data Visualization
* Analytical Thinking
* Performance Optimization Concepts

---

## 📷 Dashboard Preview

> Add screenshots of your dashboard here after uploading the project.

---

## 👨‍💻 Author

**Unique Nagpure**

This project is part of my Data Engineering and Business Intelligence portfolio, showcasing practical experience in building enterprise-scale analytical dashboards using Power BI.
