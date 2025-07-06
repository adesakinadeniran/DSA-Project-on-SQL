# 📊 Kultra Mega Stores Inventory – SQL Capstone Project

---

This repository contains my capstone project analyzing sales and inventory data for Kultra Mega Stores (KMS) using SQL Server and Power BI.

## 🏢 Company Overview

Kultra Mega Stores (KMS) is a Lagos-based company that supplies office furniture and equipment. With customers ranging from individuals to large corporations, KMS operates divisions across Nigeria, including Abuja, where this analysis is focused.

You have been engaged as a Business Intelligence Analyst to support the Abuja division using data from 2009 to 2012.

---

## 🎯 Project Goal

- Analyze historical sales and shipping data.
- Identify valuable customers, product trends, and logistics bottlenecks.
- Deliver actionable insights through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

- SQL Server – Data querying and transformation
- Power BI – Dashboarding and visual storytelling
- Power Query – Data shaping and integration
- DAX – Calculated measures and KPIs
- Excel – Original data source

---

## 📂 Dataset Details

- Source: Excel file (imported into SQL Server)
- Tables Used: Orders, Products, Customers, Regions, Shipping
- Time Range: 2009–2012
- Key Fields: Sales, Profit, Shipping Cost, Category, Segment, Region, Order Priority, Return Status

---

## 🔍 Business Questions

### 🧩 Case Scenario I: Sales & Logistics

1. Which product category had the highest sales?
2. What are the top 3 and bottom 3 regions in terms of sales?
3. What were the total sales of appliances in Ontario?
4. How can KMS increase revenue from the bottom 10 customers?
5. Which shipping method incurred the most cost?

### 🧠 Case Scenario II: Customer Segmentation

6. Who are the most valuable customers and what do they buy?
7. Which small business customer had the highest sales?
8. Which corporate customer made the most orders from 2009–2012?
9. Who was the most profitable consumer customer?
10. Which customers returned items, and what segments do they belong to?
11. Was shipping cost appropriately spent based on order priority?

---

## 💡 Key Insights

- Office Supplies had the highest overall sales.
- North Central and South West regions consistently outperformed others.
- Express Air, though fastest, incurred the most cost and wasn't always linked with high-priority orders.
- Bottom 10 customers showed low engagement and high returns—suggesting a need for retention strategy.
- Top customers often purchased furniture and technology products in bulk.

---

## 📊 Dashboard Features

- Interactive slicers: Year, Region, Segment, Shipping Method
- KPI Cards: Total Sales, Profit, Orders, Returns
- Sales by Product Category & Region
- Customer Profitability & Order Frequency
- Shipping Cost vs Order Priority

---

## 📁 Repository Structure

`bash
.
├── data/                     # Optional: SQL scripts or .bak file
├── images/                   # Dashboard screenshots
├── kms_dashboard.pbix        # Power BI file
├── sql/                      # SQL Server queries used in analysis
│   ├── case_scenario_1.sql
│   └── case_scenario_2.sql
├── README.md                 # This documentation
