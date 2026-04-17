# 🅶 for Global — Superstore Sales Analysis

## 🏦 Overview

This is the 7th project of the A–Z Data Series, shifting the focus to global retail operations. Using a multi-year dataset of global transactions, I developed an end-to-end analytical solution in Power BI to track performance across products, customers, and regional markets.

---

## 📊 Objectives

- Executive Performance: What are the high-level trends for Revenue, Profit, and Order volume?
- Customer Intelligence: Who are the key drivers of revenue, and which segments show the highest loyalty?
- Product Profitability: Which categories and sub-categories are contributing most to the bottom line, and which are underperforming?

---

## 🧹 Data Transformation & Modeling

- Star Schema was implemented for easy and simple report performance and scalability.
- Schema Design: Developed a centralized Fact table (`Facts_dm`) linked to multiple Dimension tables including `Customer_dm`, `Product_dm`, `Location_dm`, `OrderDate_dm` and others.
- Feature Engineering: Created custom logic using DAX and Power Query to handle image-based reporting, allowing for dynamic rendering of segment-specific icons within data tables.
- Data Cleaning: Aligned geographic naming conventions across markets, region, and country columns to ensure accurate mapping.

---

## 📊 Dashboard Visuals

The final Power BI dashboard includes three reporting layers:

### 1. Executive Summary
- Growth Indicators: Real-time YOY growth tracking for Revenue, Profit, and Profit Margin.
- Trend Analysis: Charts showing monthly Sales fluctuations.
- Geographic Distribution: A global map visualizing sales density across continents.

### 2. Customer Intelligence
- Segment Analysis: Breakdown of sales and orders by Consumer, Corporate, and Home Office segments.
- Top 10 Customers: A detailed table highlighting individual customer revenue, order frequency, and YOY sales trends.
- Regional Density: Identification of top-performing regions like EU and APAC based on customer count.

### 3. Product Performance
- Inventory Health: Total SKU count and average discount rates across the product catalog.
- Profitability Matrix: Comparison of "Strongest Products" versus "Weakest Products" to identify margin-draining items.

---

## ⚙️ Tools & Features Used

- Microsoft Power BI
- DAX (Data Analysis Expressions) – Developed complex measures for YOY Growth, Profit Margins, and dynamic Image URL assignments
- Power Query – Utilized for data shaping and creating the Star Schema structure

---

## 📂 Dataset

Source: The analysis is based on the **Global Superstore** dataset, containing detailed transaction records including shipping costs, discounts, and multi-regional sales data.

---

## 🧠 Key Insights

- Market Concentration: The EU and APAC regions dominate the customer density profile, accounting for the largest share of high-value clients.
- Margin Leakage: Certain "Weakest Products" show significant sales volume but near-zero or negative profit might be often tied to high discount rates.
- Segment Behavior: The Consumer segment accounts for over 50% of total sales.

---

## ➡️ Next in the Series

**H for Health**

---

## 🧑‍💻 Author

**Olusegun Japhet Abiola**

📧 Email: olusegunjapheth@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/japhetolusegunabiola