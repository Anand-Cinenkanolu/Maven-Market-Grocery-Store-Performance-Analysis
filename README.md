# Maven Market – Grocery Store Performance Analysis Dashboard

### Developed by *Anand Cinenkanolu*

This repository features a Power BI project built using the Maven Market dataset.  
The dashboard analyzes grocery store performance across product brands, stores, and countries using one clean, interactive report page.

---

## 🎯 Project Goal

Maven Market operates grocery stores across Canada, Mexico, and the United States.  
The goal of this project is to monitor and analyze:

- Monthly transactions, profit, and returns  
- Product brand performance  
- Country and store activity  
- Weekly revenue patterns  
- Revenue performance vs target  

This dashboard brings all insights together in a single page that leaders can review at a glance.

---

## 🛠️ Tools & Technologies

- Power BI Desktop  
- Power Query (data shaping)  
- DAX (Data Analysis Expressions)  
- Star-schema relational modeling  
- Maven Market CSV Dataset  
- Time intelligence functions  

---

## 📊 Dashboard Overview

This project contains **one dashboard page** that includes all visuals and KPIs used in the analysis.

### 1. KPI Cards
- Total Transactions  
- Total Profit  
- Total Returns  
- Month-over-Month % Change  
- Trend indicators for each KPI  

### 2. Top 30 Product Brands Matrix
Displays:
- Total Transactions  
- Total Profit  
- Profit Margin  
- Return Rate  
- Top N filter showing **Top 30 brands** by transaction volume  

### 3. Map – Transactions by Store City
- Shows total transactions at each store location  
- Includes **country slicer** (US, Mexico, Canada)

### 4. Treemap – Transactions by Country
- Visual comparison of transaction volume by country  

### 5. Weekly Revenue Trend (Column Chart)
- Revenue by week across the year  
- Highlights:
  - Week of December 6 (~45K revenue)  
  - Week of July 19 (~35K revenue)  

### 6. Revenue vs Target (Gauge)
- Current month revenue  
- Target = last month's revenue + 5%  
- Indicates whether revenue is above or below target  

![Over view]()

---

## 🗂️ Data Modeling

A clean relational star-schema model was built.

### Dimension Tables
- Products  
- Customers  
- Stores  
- Regions  
- Calendar  

### Fact Tables
- Transactions  
- Returns  

### Modeling Details
- Relationships created using primary and foreign keys  
- One-to-many cardinality  
- Single-direction filtering  
- Calendar table expanded with:
  - Year, Quarter, Month  
  - Start of Week  
  - Start of Month  
  - Month Name  
- All foreign keys hidden from Report View  
- Proper formatting for currency, dates, and locations  

> Insert your data model image  

![Data Modeling]()

> **Power BI Live Dashboard Link:**  
![Link]()


## 📣 Contact

For queries, collaboration opportunities, or feedback, feel free to reach out:

- 📧 [**Email**](anandcinenkanolu@gmail.com)
- 💼 [**LinkedIn**](https://www.linkedin.com/in/Anand-Cinenkanolu/)
- 🗂️ [**Portfolio**](https://codebasics.io/portfolio/Anand-Cinenkanolu)
