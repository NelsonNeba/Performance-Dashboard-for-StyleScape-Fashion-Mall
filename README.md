


# 👗 **Sales Excellence in Style: Crafting a Cutting-Edge Performance Dashboard for StyleScape Fashion Mall**

![Dashboard](https://github.com/NelsonNeba/Performance-Dashboard-for-StyleScape-Fashion-Mall/blob/main/Assets/Dashboard.png)

This project was a hands-on opportunity to master **Power BI**, develop **data visualization** expertise, and apply these skills to a real-world scenario in the **retail fashion industry**. I designed and deployed an interactive dashboard that delivered **real-time sales insights** to decision-makers at StyleScape’s Nigerian division of StyleScape Fashion Mall, enabling more **strategic and efficient** decision-making.

---

## 🎯 **Project Aim**
To develop an **automated, insightful sales dashboard** that:

- 📅 Breaks down sales performance **by weekday**, with week-over-week comparisons  
- 🔁 **Auto-updates** weekly with no manual intervention  
- 📊 Defines and tracks key KPIs like customer count, Weekly sales growth rate, and top products  

---

## 🏬 **Business Overview & Problem Statement**

**StyleScape Fashion Mall** operates across Africa and heavily depends on **weekly sales performance data** to track progress and make data-driven decisions. However, the **Regional Sales Manager** of the Nigerian division faced major challenges:

### ❌ Key Obstacles

- **Limited Visual Analytics**: Numeric-heavy reports made trend analysis difficult  
- **Manual Reporting**: Time-consuming and error-prone weekly computation  
- **Undefined KPIs**: Lack of standardized performance metrics  
- **Inconsistent Reporting**: No unified report format or tracking methodology  

---

## 📌 **Rationale for the Project**

An **interactive sales dashboard** would:

- Provide **clear, visual insights** at a glance  
- Enable **automated, real-time** sales tracking  
- Help identify **sales trends** and performance issues promptly  
- Improve overall **strategic decision-making**

---

## 🛠 **Tech Stack**

![SQL](https://img.shields.io/badge/SQL-Data_Extraction-blue)  
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard_Creation_|_Modeling_|_Visualizations-yellow)  
![DAX](https://img.shields.io/badge/DAX-KPI_Measurement-orange)  
![Power_Query](https://img.shields.io/badge/Power_Query-Transformation-green)  
![Report Automation](https://img.shields.io/badge/Automation-Real_Time_Updates-purple)

---

## 📚 **Key Learning Points**

- 🧠 DAX (Data Analysis Expressions)  
- 🧮 Database Querying with SQL  
- 🎨 Data Visualization Techniques  
- 🔗 Data Modeling and Relationships  
- 🧼 Data Transformation  
- ⚙️ Report Automation

---

## 🧭 **Project Workflow**

1. **Data Aggregation**  
   - Queried SQL Server database to extract necessary sales and customer data

2. **Data Integration**  
   - Connected Power BI directly to the SQL Server for real-time data updates

3. **Data Modeling**  
   - Built robust relationships between tables (Sales, Customers, Products, Stores)

4. **Analysis & Visualization**  
   - Defined KPIs and developed interactive visualizations in Power BI

5. **Interactive Visualization** 
    - uilt drill-through,    filterable, and visually    dynamic dashboard

---

## 🗂 **Data Description**

### 🏢 StoreLocation  
- `StoreID`, `Location`

### 👗 Products  
- `ProductID`, `ProductName`, `SubCategory`, `ProductCategory`, `Price`

### 👥 Customers  
- `CustomerID`, `CustomerName`, `Location`

### 👔 Sales Personnel  
- `PersonnelID`, `PersonnelName`, `DateJoined`, `StoreID`

### 🧾 Sales Orders  
- `OrderID`, `SalesDate`, `ProductID`, `CustomerID`, `PersonnelID`, `SalesChannel`, `Quantity`, `SalesAmount`, `PaymentMode`, `StoreID`


![ERD](https://github.com/NelsonNeba/Performance-Dashboard-for-StyleScape-Fashion-Mall/blob/main/Assets/ERD.png)


---

## 📈 **Key Performance Indicators (KPIs)**

- 💰 **Total Sales**  
- 🧾 **Total Orders**  
- 🧑‍🤝‍🧑 **Number of Customers (Weekly)**  
- 💳 **Average Order Value**  
- 🔝 **Top-Selling Products**
- 📈 **Sales Growth Rate (%)**

---

## 📊 **Dashboard Features**

- **Weekly Sales Breakdown**: Visualized sales by weekday with week-over-week comparisons  
- **Top Products & Channels**: Insight into best-sellers and whether they were sold online or in-store  
- **Customer Insights**: Number of unique customers per week  
- **Trend Analysis**: Conditional formatting and color-coded visuals to highlight performance changes  
- **Dynamic Filters**: Filter by product category, store location, and sales channel

---

## 💡 **Why This Dashboard Matters**

- 🧠 **Instant Insight**: At-a-glance view of how sales are performing  
- ⏱ **Time-Saving**: Eliminates manual reporting  
- 📊 **Strategic Edge**: Empowers data-backed decision-making  
- 📦 **Operational Efficiency**: Helps allocate resources based on data trends

---
## 📈**Insights & Observations**
**🔍 1. Sales Channel Performance**

- *Insight*: 51.47% of sales originated from in-store purchases, with the online channel showing a 20.15% Week-over-Week growth.

- *Recommendation*: Increase marketing investment in online platforms to capitalize on growing digital traffic.


**🔍 3. Top Products Driving Revenue**

- *Insight*: Women’s Dresses and Shoes contributed over 55% of total revenue.

- *Recommendation*: Expand product lines in these categories and feature them prominently in promotions.

**🔍 4. Average Order Value (AOV)**

- *Insight*: AOV is high at ~135.7k for online orders comapared to ~123k for instore orders.

- *Recommendation*: Encourage upselling in instore locations using personalized product recommendations.

**🔍 5. Store Location Comparison**

- *Insight*: Lekki Mall outperformed all other locations, generating 21.84 % of national sales.

- *Recommendation*: Analyze operational strategies at Lekki and replicate high-performing tactics in underperforming locations.

## ✅ **Outcomes**

- 🎯 Provided the Regional Sales Manager with a **centralized, accurate, and automated** dashboard  
- 🔁 Reduced time spent on weekly reporting by over **70%**  
- 📈 Enabled better **sales strategy alignment** across departments

---




[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

