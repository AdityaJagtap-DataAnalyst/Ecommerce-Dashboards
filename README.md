🛒 Olist E-Commerce Analytics Dashboard

A complete end-to-end Business Intelligence project built using SQL, ETL pipelines, and Power BI to analyze Brazil’s largest multi-vendor marketplace — Olist.
This dashboard transforms raw transactional data into actionable insights for Sales, Products, Sellers, and Order Delivery Performance.

🚀 Project Overview

This project delivers a full analytical solution covering:

Data Extraction → Transformation → Loading (ETL)

SQL-based data cleaning & feature engineering

Power BI data modeling (Star Schema)

DAX measures for KPIs

Interactive dashboards for business stakeholders

The final dashboard helps answer critical business questions such as:

How are sales trending by month, product category, and region?

What percentage of orders are delayed and why?

Which sellers drive the most revenue and fulfillment?

Which products receive the best ratings and fastest delivery times?

How do payment types influence order delays?

📌 Live Dashboard Preview:
👉 Click here to view the Power BI Report

🧰 Tech Stack
Component	Tools Used
ETL / Data Prep	Python, SQL, Power Query, Excel
Database	SQL Server / PostgreSQL
Data Modeling	Star Schema (Fact + Dimension Tables)
BI & Visualization	Power BI (DAX, Bookmarks, Slicers, Maps)
Deployment	Power BI Service
🔄 ETL Process (Smart & Professional Explanation)
1️⃣ Data Extraction

Raw Olist datasets were sourced from Kaggle, containing:

Orders

Customers

Sellers

Order Items

Payments

Reviews

Products

Geolocation

2️⃣ Data Transformation (SQL + Power Query)

Performed:

Handling missing values

Normalizing product categories

Creating date, rating, and payment type dimensions

Fixing inconsistent customer/seller IDs

Calculating delivery delays and freight metrics

Feature engineering:

delivery_delay_days

order_fulfilled_flag

category_performance_score

3️⃣ Data Loading

Final cleaned tables were loaded into Power BI using:

Star Schema design

Fact Tables: orders, order_items, payments, reviews

Dimension Tables: customers, products, sellers, date_dim, geolocation

This structure supports faster DAX queries and smooth dashboard performance.

📊 Dashboard Features (Page-by-Page Explanation)
📁 1. Business Overview

Key performance indicators:

Total Sales: 15.84M

Total Orders: 99.44K

Orders Delayed: 6.57%

Average Delivery Time: 12 days

Visual highlights:

Monthly sales trend

Delivery vs non-delivery segmentation

Sales by states (interactive map)

Outlier/spike detection by product category

Order delays by payment type

📁 2. Sales Overview

KPIs:

Total Price: 13.22M

Freight Value: 2.20M

Total Revenue: 15.42M

Insights:

Year-wise cumulative sales (2016–2018)

Top 10 product categories by order volume

Bottom 10 performing categories

Combined sales vs freight cost trend

📁 3. Product Overview

KPIs:

Unique Products: 32.22K

Insights:

Product-wise sales contribution

Payment method distribution by product

Average delivery time by product category

Average review score

Monthly product count

📁 4. Sellers Overview

KPIs:

Total Sellers: 3095

Active Sellers: 2970

Avg Seller Rating: 4.16

Late Deliveries: 6.77%

Insights:

Orders fulfilled per seller

Delayed orders by state

Top sellers by revenue

Monthly seller order trends

🧠 Smart Work & Value Addition

Here’s what makes your project stand out professionally:

✔ End-to-end pipeline (ETL → SQL → Data Model → BI)
✔ Advanced DAX measures (ratings, delays, revenue, freight)
✔ Outlier detection added (unique feature)
✔ Bookmark navigation + clean slicer UX
✔ State-level geographic insights (Brazil map)
✔ Strong storytelling with KPIs
✔ 4-page structured dashboard matching enterprise standards
