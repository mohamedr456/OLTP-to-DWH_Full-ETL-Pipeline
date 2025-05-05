# 📦 OLTP-to-DWH | ETL Pipeline with Dimensional Data Modeling & Power BI Dashboard

This "FCAI | DWH-Course" project demonstrates the end-to-end process of transforming transactional (OLTP) sales data into a structured Data Warehouse (DWH) using **SQL Server Integration Services (SSIS)**, with dimensional modeling and insightful **Power BI** dashboards.

---

## 📚 Project Overview

- **Source**: Monthly sales CSV files (2019)
- **ETL Tool**: SQL Server Integration Services (SSIS)
- **DWH Platform**: SQL Server Management Studio (SSMS)
- **BI Tool**: Power BI Desktop
- **Goal**: Build a centralized DWH from OLTP files and enable actionable insights for business users 

---

## 🛠️ Technologies Used

- SQL Server Integration Services (SSIS)
- SQL Server Management Studio (SSMS)
- Power BI Desktop
- Visual Studio (for SSIS development)
- T-SQL
- Data Flow & Control Flow Components
- Dimensional Data Modeling (Star Schema)

---

## 🧱 Data Warehouse Design

### 📚 KPIs & Beuisness statments

### KPIs Beneficiaries
 – Sales tracking
 – Marketing planning
 – Operations
 – Inventory

### Business Insight Areas
 – Sales Performance Over Time
 – Product Performance & Sales Trends
 – Customer Behavior & Cross-Selling
 – Geographical Performance
 – Marketing Optimization & Ad Timing
 – Sales Metrics & Efficiency

### KPIs List

**Sales Performance Over Time**

1. Total Revenue = SUM(Quantity Ordered : Price Each)
2. Total Orders = COUNT(DISTINCT Order ID)

**Product Performance & Sales Trends**

1. Total Quantity Sold per Product = SUM(Quantity Ordered)
2. Revenue per Product = SUM(Quantity Ordered: Price Each)
3. Average Price of Products Sold

**Geographical Performance**

1. Revenue by City = Group by parsed city from address
2. Quantity Sold by City
3. Best Performing City (by revenue and/or quantity)

**Marketing Optimization & Ad Timing**

1. Peak Purchase Hour = Hour with highest of orders
2. Peak Purchase Day of Month
3. Ad Recommendation Hour = Hour with most high-value purchases

**Sales Metrics & Efficiency**

1. Average Order Value (AOV) = Total Revenue / Number of Orders
2. Lowest Revenue Product
3. Highest Revenue Product
4. Orders with High-Value Purchases (e.g. > $500) = Flagged for premium buyers


### 🗂️ Star Schema


---

## ⚙️ ETL Pipeline (SSIS)

### 📥 Extraction
 

### 🧹 Transformation
 

### 📤 Loading
 

---

## 📊 Power BI Dashboard


---

## 📂 Folder Structure

