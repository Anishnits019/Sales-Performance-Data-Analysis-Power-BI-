# Power BI Sales Analysis Project

## Business Problem
This project analyzes overall sales performance to identify trends, regional performance differences, and product-level insights.  
The goal is to help stakeholders understand **where sales are growing or declining** and **which products and regions need attention**.

---

## Dataset
- **Source:** Structured sales dataset (Excel)
- **Total Rows:** 56,214
- **Time Period:** 2020 – 2022
- **Tables Used:**
  - Sales (fact table)
  - Product
  - Customer
  - Date

The dataset contains order-level sales transactions including quantity, revenue, cost, profit, product category, customer region, and order date.

---

## Tools & Technologies
- **Power BI Desktop**
- **Power Query** (data cleaning & transformation)
- **DAX** (measures and business logic)
- **Microsoft Excel** (data source)

---

## Data Preparation
- Removed duplicate records
- Handled missing values
- Standardized date formats
- Created a proper **star schema**
- Built relationships between Sales, Product, Customer, and Date tables
- Hid technical columns and helper measures in the data model

---

## Key KPIs
- Total Sales
- Total Profit
- Profit Margin (%)
- Year-over-Year (YoY) Sales Growth
- Top Performing Products
- Regional Sales Contribution

All KPIs were created using **DAX measures** (no calculated columns for aggregations).

---

## Dashboards & Visuals
- Sales trend by year and month
- Regional sales comparison
- Product-wise performance analysis
- KPI cards for high-level metrics
- Interactive slicers for Year, Region, and Product Category

---

## Key Insights
- Sales declined significantly in **Q3**, mainly due to an increase in product returns.
- The **Pacific Region** consistently underperformed compared to other regions.
- A small number of products contributed to a large share of total revenue.
- Profit margins varied widely across product categories, indicating pricing inefficiencies.

---

## Business Recommendations
- Investigate return reasons for products impacting Q3 performance.
- Focus marketing and operational improvements on underperforming regions.
- Re-evaluate pricing and cost structure for low-margin products.
- Prioritize high-performing products for future growth.

---

## Repository Structure
