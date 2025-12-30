# 🍕📊 Pizza Sales Analytics  
## From Raw Data to Business Insights & Interactive Dashboard

This project analyzes pizza sales performance using **PostgreSQL for SQL-based data analysis** and **Microsoft Excel for dashboard visualization**. The goal is to understand customer purchasing behavior, identify top- and low-performing pizzas, and deliver actionable insights that support business decision-making.

---

## 🎯 Project Objectives
- Analyze overall revenue and sales performance  
- Identify best-selling and underperforming pizzas  
- Understand customer ordering behavior by day and time  
- Build an interactive Excel dashboard for stakeholders  

---

## 📂 Dataset Overview
The dataset contains detailed pizza order information, including:
- Order ID  
- Pizza name, category, and size  
- Quantity sold  
- Unit price and total price  
- Order date and time  

📁 The dataset is included in this repository.

---

## 🧰 Tools & Technologies
- **PostgreSQL** – Database management and SQL analysis  
- **Microsoft Excel** – Dashboard creation and visualization  
- **Power Query** – Data import and transformation  
- **Pivot Tables & Charts** – KPI reporting and insights  

---

## 🔄 Project Workflow

###  Step 1: Data Import
The raw dataset was imported into **PostgreSQL**, and a table named `pizza_sales` was created with the following columns: order_id, pizza_id, pizza_name_id, quantity,
order_date, order_time, unit_price, total_price

---

### Step 2: Data Cleaning
Data cleaning was performed to ensure accuracy and consistency:
- Removed blank rows and invalid records  
- Corrected date and time formats  
- Standardized pizza categories and sizes  
- Ensured consistency in quantity and pricing fields  

---

### Step 3: SQL Data Analysis
SQL queries were used to extract key metrics and uncover trends

# 📊 Dashboard Creation (Excel)

The results from SQL analysis were exported to Microsoft Excel to build an interactive dashboard using:

KPI cards (Total Revenue, Total Orders, Average Order Value),
Line charts for time-based sales trends,
Bar and donut charts for category and size analysis,
Slicers for filtering by date, category and size

Dashboard Preview:
https://github.com/mayank235-ai/Pizza_sales_analysis/blob/main/pizza_dashboad.png

**📈 Key Insights**
 
*Sales Performance*

Total Revenue: $817,860
Highest sales on Fridays and Saturdays

*Peak ordering hours*:

Lunch: 12 PM – 1 PM
Evening: 5 PM – 8 PM

*Product Performance*

Most ordered size: Large
Top-selling pizza: Classic Deluxe Pizza
Highest revenue category: Classic Pizzas

*Low-Performing Products*

Least ordered pizzas:
Brie Carre
Mediterranean

**📁 Repository Structure**

Pizza_Sales_Analysis

├── pizza_sales.csv

├── queries.sql

├── pizza_sales_dashboard.png

└── README.md

**🚀 Conclusion**

This project demonstrates practical experience in SQL querying, data cleaning, KPI analysis, and dashboard development. It reflects a complete, real-world data analytics workflow — converting raw data into clear insights that support business decision-making.








