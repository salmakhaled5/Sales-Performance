# 🧠 Data Analytics Power BI Project — Sales Performance Dashboard

## 📊 Overview

This project presents a comprehensive **Sales Performance Analysis** built using **Power BI**, showcasing data-driven insights into product performance, customer behavior, store efficiency, and currency impact across multiple regions.

The goal of this analysis is to transform raw sales data into actionable intelligence that supports **strategic decision-making**, **operational optimization**, and **performance monitoring**.

---

## 🗂️ Project Objectives

1. **Design a professional Power BI dashboard** with multiple analytical views.
2. **Implement a Snowflake Schema model** to improve data efficiency and scalability.
3. **Perform data cleaning and transformation** in Power Query to ensure consistency and reliability.
4. **Develop DAX measures** to calculate KPIs such as Total Sales, Profit Margin, Orders, and more.
5. **Generate analytical and strategic insights** through interactive visualizations.

---

## ⚙️ Data Model

The model follows a **Snowflake Schema**, connecting the following key tables:

- **Sales** – Transaction data with product, customer, and store references.
- **Customers** – Customer demographics and geolocation data.
- **Products** – Product details including brand, category, and pricing.
- **Stores** – Store-level data for regional and size analysis.
- **Exchange Rates** – Currency rates linked to sales via date and currency code.

This structure ensures scalability, optimized relationships, and clear data lineage.

---

## 🧹 Data Preparation (Power Query)

Data cleaning and transformation steps include:

- Fixed date format inconsistencies (day/month vs. month/day)
- Standardized country, state, category, and subcategory names
- Removed currency symbols and normalized numeric fields
- Added “Order Type” column (Online vs In-store)
- Created and connected a **Date Table** for time intelligence
- Handled missing delivery dates (in-store sales)
- Normalized product hierarchy using separate **Category** and **Subcategory** tables

---

## 🧮 Key DAX Measures

| Measure | Description |
|----------|-------------|
| **Total Sales (USD)** | Total sales in USD |
| **Total Sales (Local)** | Sales converted from local currency using exchange rates |
| **Total Profit (USD)** | Sales revenue minus cost |
| **Profit Margin %** | Profitability ratio |
| **Orders per Customer** | Average number of orders per customer |
| **Average Unit Price** | Mean selling price per product |
| **Average Unit Cost** | Mean cost per product |

---

## 📈 Dashboard Pages

### 🧭 Executive Overview
Provides a high-level summary of total sales, profit, margin, and order trends over the last quarter.
Includes quarter-over-quarter and year-over-year performance comparisons.

![Executive Overview](Executive%20Overview.png)

---

### 🛒 Product Performance
Displays product-level insights such as best-selling and underperforming categories, brands, and individual products.
Includes a treemap visualization for **Category → Subcategory** hierarchy.

![Product Performance](Product%20Performance.png)

---

### 🏬 Store Analysis
Evaluates store performance by region and size.
Highlights top and low-performing stores, in-store vs. online sales, and regional profitability variations.

![Store Analysis](Store%20Analysis.png)

---

### 🌍 Currency & Exchange
Visualizes the impact of currency fluctuations on revenue.
Shows exchange rate trends over time and their relationship with local vs. USD-denominated sales.

![Currency & Exchange](Currency%20%26%20Exchange.png)

---

### 👥 Customer Insights
Analyzes customer demographics, behavior, and purchasing patterns.
Includes metrics such as customer age distribution, order frequency, and regional segmentation.

![Customer Insights](Customer%20Insights.png)

---

## 💡 Key Insights

- **Electronics and Home Appliances** are consistently top-performing categories.
- **Games and Toys** underperformed this quarter, mainly due to seasonal demand drop and low visibility.
- **France and Stores 2, 13, 14, and 17** showed weaker performance compared to other markets.
- Seasonal peaks strongly influence sales patterns, especially around holidays and school vacations.
- Non-seasonal categories (e.g., small electronics) provide stable baseline revenue.

---

## 🚀 Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Excel / CSV / Google Sheets (Source Data)**
- **Snowflake Schema Data Modeling**
- **Power BI Bookmarks** for dynamic navigation between analytical views

---

## 📘 Documentation

The project includes a **Data Cleaning Process Report (PDF)** detailing:
- Step-by-step Power Query transformations
- Cleaning rationale
- Data model design explanation
- Screenshot samples of M code

---

## 🧭 Strategic Recommendations

- Increase marketing investment for underperforming categories (e.g., Games & Toys)
- Align promotions with seasonal demand cycles
- Improve visibility in underperforming regions (e.g., France)
- Use predictive analytics in Power BI to forecast sales and plan inventory



---

