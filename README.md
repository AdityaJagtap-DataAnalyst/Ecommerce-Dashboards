# 🛒 Olist E-Commerce Analytics Dashboard

## 📊 Overview / Description
The **Olist E-Commerce Analytics Dashboard** is a complete end-to-end Business Intelligence project built using **SQL, ETL pipelines, and Power BI**.  
It analyzes Brazil’s largest multi-vendor marketplace — Olist — and converts raw transactional data into actionable insights across **Sales**, **Products**, **Sellers**, and **Order Delivery Performance**.

This project enables business leaders to understand marketplace performance, track revenue trends, and make data-driven decisions.

---

## 🚀 Project Overview
- Data Extraction → Transformation → Loading (ETL)  
- SQL-based data cleaning & feature engineering  
- Power BI data modeling (Star Schema)  
- DAX measures for KPI calculations  
- Fully interactive dashboards for multiple business domains  

The dashboard answers key questions such as:
- How are sales trending by month, category, and region?  
- What percentage of orders are delayed and what are the reasons?  
- Which sellers generate the highest revenue and fulfill the most orders?  
- Which product categories perform best in reviews and delivery time?  
- How do payment types affect order delays?  

---

## 🔗 Live Dashboard Preview
👉 **[Click here to view the Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMDgyYjk1NjctYmJmMy00NWQ0LWFjNWMtM2M0Yzk1Y2FhOWViIiwidCI6IjdjNjZkNGIyLTVmY2QtNGRlYi1hMDQ4LTg1NGQ4ZWEyNDM3MSJ9)**

---

## 🧰 Tech Stack
- **ETL / Data Prep:** Python, SQL, Power Query, Excel  
- **Database:** SQL Server  
- **Data Modeling:** Star Schema (Fact & Dimension Tables)  
- **BI & Visualization:** Power BI (DAX, Slicers, Bookmarks, Maps)  
- **Deployment:** Power BI Service  

---

## 🔄 ETL Process

### 1️⃣ Data Extraction  
Raw Olist datasets sourced from Kaggle, including:  
- Orders  
- Customers  
- Sellers  
- Order Items  
- Payments  
- Reviews  
- Products  
- Geolocation  

### 2️⃣ Data Transformation (SQL + Power Query)  
Performed:  
- Handling missing values  
- Normalizing product categories  
- Creating date, rating, and payment type dimensions  
- Fixing inconsistent customer/seller IDs  
- Calculating delivery delays & freight metrics  
- Feature engineering such as:  
  - `delivery_delay_days`  
  - `order_fulfilled_flag`  
  - `category_performance_score`  

### 3️⃣ Data Loading  
Final cleaned tables were loaded into Power BI using:  
- Star Schema design  
- Fact Tables: orders, order_items, payments, reviews  
- Dimension Tables: customers, products, sellers, date_dim, geolocation  

This improves DAX performance and ensures optimized visuals.

---

## 📊 Dashboard Features

### 📁 1. Business Overview
**Key Metrics:**  
- Total Sales: **15.84M**  
- Total Orders: **99.44K**  
- Orders Delayed: **6.57%**  
- Average Delivery Time: **12 days**  

**Visuals Included:**  
- Monthly sales trend  
- Delivery vs non-delivery segmentation  
- Sales by state (map)  
- Outlier/spike detection by product category  
- Order delays by payment type  

---

### 📁 2. Sales Overview
**KPIs:**  
- Total Price: **13.22M**  
- Freight Value: **2.20M**  
- Total Revenue: **15.42M**  

**Insights:**  
- Year-wise cumulative sales  
- Top 10 product categories  
- Bottom 10 product categories  
- Sales vs freight comparison  

---

### 📁 3. Product Overview
**KPI:**  
- Unique Products: **32.22K**  

**Insights:**  
- Sales by product category  
- Payment method distribution  
- Average delivery time by product  
- Average review score by product  
- Monthly product count trend  

---

### 📁 4. Sellers Overview
**KPIs:**  
- Total Sellers: **3095**  
- Active Sellers: **2970**  
- Avg Seller Rating: **4.16**  
- Late Deliveries: **6.77%**  

**Insights:**  
- Orders fulfilled per seller  
- Delayed orders by state  
- Top sellers by revenue  
- Monthly seller order count  

---

## 🧠 Work
✔ End-to-end pipeline (ETL → SQL → Data Model → BI)  
✔ Advanced DAX calculations for delay %, revenue, ratings, fulfillment  
✔ Outlier detection for monthly category trends  
✔ Clean, intuitive slicer and navigation experience  
✔ Geographic analysis using Brazil state maps  
✔ Strong KPI storytelling across all pages  
✔ Enterprise-standard dashboard layout and structure

