# SQL-Python-Ecommerce

This project analyzes an **E-Commerce dataset analysis** using **SQL queries** and **Python** for insights & visualizations.  
It explores **customer behavior, sales patterns, and business performance** by answering both **basic and advanced analytical questions**.

---

## 📊 Project Overview
The dataset includes information about:
- **Customers** – Demographic details (city, state, ID mapping)  
- **Orders** – Order IDs, timestamps, status  
- **Order Items** – Product ID, seller ID, quantity, price, freight value  
- **Products** – Category, dimensions, weight  
- **Payments** – Payment type, installments, value  
- **Sellers** – Seller details and performance  
- **Geolocation** – City, state, latitude, longitude  

Using these tables, SQL was used to extract insights, and Python (Pandas, NumPy, Matplotlib, Seaborn) was used for further analysis.

---

## 🔎 Queries Performed

### ✅ Basic
- Unique customer cities  
- Orders placed in **2017**  
- Sales per product category  
- % of orders with installments  
- Customers count per state  

### 📈 Intermediate
- Orders per month in **2018**  
- Avg. products per order (by city)  
- % revenue by category  
- Correlation: product price vs. purchase frequency  
- Revenue per seller (ranked)  

### 🚀 Advanced
- Moving average of order values per customer  
- Cumulative sales per month (by year)  
- Year-over-year sales growth rate  
- Customer retention (within 6 months)  
- Top 3 spenders per year  

---

## 🛠️ Tech Stack
- **SQL** – Data extraction, transformations, aggregation  
- **Python** – Data cleaning, analysis & visualization  
  - Pandas, NumPy, Matplotlib, Seaborn  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-data-analysis.git
   cd ecommerce-data-analysis
   
2. Import dataset files into your SQL database (MySQL/PostgreSQL/SQLite).

3. Run queries from Questions.txt or queries.sql (if provided).

4. Open Ecommerce_python_sql.ipynb in Jupyter Notebook to view the Python analysis.
