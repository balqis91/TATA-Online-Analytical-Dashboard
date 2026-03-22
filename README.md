# TATA-Online-Analytical-Dashboard
#  TATA Online Retail Dashboard  
<img width="1173" height="642" alt="image" src="https://github.com/user-attachments/assets/dc35fe3a-f618-4b99-b683-132d3a416d76" />

# Dashboard Preview
![Dashboard]([your-image-link-here](https://app.powerbi.com/view?r=eyJrIjoiZmM0ODBhNzgtMTczMi00NmFiLTk3NWUtOWQzNWEwNDE1MjM3IiwidCI6IjU2M2QwNDI1LTBlMDQtNGVlMi05NTE3LTNjYmIxMzMyZTQ5OCJ9))

##  Overview  
This project focuses on analyzing sales performance for **TATA Online Retail** using an interactive dashboard.  
The goal was to extract actionable insights from retail transaction data, identify key trends,  
and present them in a user-friendly format for decision-making.  

The dashboard provides a comprehensive view of:  
-  Total Sales Quantity  
-  Order Volume  
-  Registered Customers  
-  Total Revenue & Average Price  
-  Geographical Sales Distribution  

---

##  User Requirement  
The business required a solution to:  
- Monitor **total sales, orders, and revenue**.  
- Identify **top-performing products** and their contribution to revenue.  
- Analyze **sales patterns by day, month, and year**.  
- Visualize **geographical distribution of sales**.  
- Create a **clear, interactive dashboard** for management use.  

---

##  About the Dataset  
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)   
- **Period Covered:** December 2010 – December 2011  
- **Records:** ~500,000 transactions  
- **Key Columns:**  

| Column       | Description |
|--------------|-------------|
| `InvoiceNo`  | Unique transaction number |
| `StockCode`  | Product code |
| `Description`| Item description |
| `Quantity`   | Number of units purchased |
| `InvoiceDate`| Date and time of transaction |
| `UnitPrice`  | Price per unit (£) |
| `CustomerID` | Unique customer identifier |
| `Country`    | Customer’s country |

---

##  Data Cleaning & Preparation  
Steps taken to ensure data quality:  
- Removed **duplicates** and **null values** (especially in `CustomerID` and `Description`).  
- Excluded **cancellations and refunds** (negative quantities).  
- Converted `InvoiceDate` into **Day, Month, and Year** for time-based analysis.  
- Created a new field:  
<img width="1536" height="713" alt="image" src="https://github.com/user-attachments/assets/8a9ebf7c-0178-42d0-a402-fbd7b2ea9594" />

- Standardized country names and grouped minor contributors under “Others.”  

---

##  Modelling & Visualization  
The analysis and visualization were performed using **Power BI**.  

**Key Visuals:**  
- **KPIs:** Total Quantity, Orders, Revenue, Average Price, Registered Customers  
- **Bar Chart:** Revenue by Top Products  
- **Line Chart:** Revenue by Days of the Week  
- **Pie Chart:** Revenue by Year  
- **Map Visualization:** Revenue & Quantity by Country  
- **Monthly Trend:** Revenue progression over time  

 
---

##  Findings  
- **Top Product:** *Zinc T-Light* contributed the highest revenue (£4.2K).  
- **Sales Growth:** 2011 generated **92%** of total revenue, indicating strong year-on-year growth.  
- **Best Sales Days:** Highest revenue on **Thursday (£2.1M)**, lowest on **Sunday (£0.8M)**.  
- **Regional Performance:** **Europe** was the strongest market (£8.19M).  
- **Average Price:** £4.61 per item sold.  

---

##  Conclusion  
The dashboard reveals that **Europe and Zinc T-Light products drive the majority of revenue**,  
with clear weekly sales patterns.  

**Recommendations:**  
- Focus marketing campaigns on **top products** and **peak days (Tues–Thurs)**.  
- Develop targeted promotions for **low-revenue days (Sunday)**.  
- Maintain strong engagement in **European markets**, while exploring growth in underperforming regions.  

This dashboard provides a strong foundation for **ongoing business monitoring and decision-making**.  

---

##  Tools Used  
- **Power BI** – Dashboard creation & visualization  
- **Excel / CSV** – Initial data review & preparation  
- **DAX / Power Query** – Data cleaning and transformation  

---

 Created by Balikisu Ajoke Oniyide. 


