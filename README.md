
# 📊 Sales Insights Data Analysis Project

## Overview

This project analyzes sales data using **MySQL** for data management and **Power BI** for interactive reporting. The objective is to extract actionable insights from transactional data, focusing on total sales, customer behavior, product performance, and sales trends over time.

---
### THE PDF FILE FOR DATA VISUALIZATION:  [📥 Download mysalesreport.pdf](./mysalesreport.pdf)


## 🔍 Project Scope & Workflow

### 1. Data Import  
- Imported the dataset by running a `.sql` dump file into MySQL Server 8.0.

### 2. Data Cleaning  
- Connected Power BI to the MySQL database.  
- Cleaned and prepared data by removing unnecessary columns, renaming fields, and correcting data types.

### 3. Data Transformation  
- Created calculated columns and measures in Power BI, e.g.:  
  - **Total Sales** = `SUM(transactions[sales_amount])`  
  - **Normalized Sales** = `SUM(transactions[norm_amount])`

### 4. Data Modelling  
- Defined relationships between tables using appropriate cardinality (one-to-many) and filter directions for accurate reporting.

### 5. Data Visualization  
- Built interactive Power BI reports with bar graphs, line charts, and other visuals to highlight sales insights.

---

## 📈 Sales Report Summary

### Key Revenue Contributors  
- **Electricalsara Stores** is the top customer, generating ₹413 million in revenue, significantly ahead of others.  
- Other key customers: Electricalslytical, Excel Stores, Premium Stores, Nixon (₹44M–₹50M each).  
- Revenue concentration indicates reliance on a single major account.

### Sales Volume Leaders  
- Electricalsara Stores leads in volume with 0.65 million units sold.  
- Premium Stores follows with 0.28 million units.  
- High revenue aligns with high volume, reinforcing strategic importance.

### Market Performance  
- **Delhi NCR** dominates with ₹520 million revenue and ~1 million units sold.  
- Mumbai and Ahmedabad show moderate performance.  
- Emerging/underperforming markets: Bhubaneswar, Bengaluru, Patna may need focused marketing.

### Product Insights  
- An unnamed product listed as “(Blank)” accounts for ₹469 million, indicating potential data issues or a highly successful SKU needing clarity.  
- Other top products: Prod040, Prod159, Prod065, Prod018 (₹16M–₹24M revenue each).

### Revenue Growth Trends  
- Observed steady upward trend from 2018 to 2020, suggesting effective sales strategies and market engagement.  
- Monthly-level patterns require deeper analysis.

---

## 🛠️ Technology Stack

- **MySQL Server 8.0** — data storage and querying  
- **Power BI** — data visualization and report creation  
- **SQL** — data extraction and manipulation  
- **Power Query M** — data transformation inside Power BI

---

## 📥 Report

You can download the detailed visualization report here:  
[mysalesreport.pdf](./mysalesreport.pdf)

---

## 👩‍💻 Author

**Manreet Kaur**  
GitHub: [Manreet30](https://github.com/Manreet30)

---

