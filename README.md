# Amazon Product Sales Analysis: Power BI Dashboard

## 📊 Overview

This project presents an **interactive Power BI dashboard** analyzing year-to-date (YTD) sales, product category performance, review metrics, and sales trends for Amazon products. The goal is to derive actionable business insights and improve product strategies through visual storytelling.

The dashboard visualizes key KPIs, monthly and weekly sales trends, category-level contributions, and product-level comparisons to highlight what’s driving performance — and what’s not.

---

## 📁 Repository Contents

| File Name                         | Description                                                      |
|----------------------------------|------------------------------------------------------------------|
| `Amazon_Products_Dashboard.pbix` | Power BI dashboard file with all visuals and filters             |
| `amazon_sales_data.csv`          | Source dataset used to build the dashboard (YTD sales & reviews) |
| `dashboard_screenshots/`         | Folder containing exported images of the dashboard               |
| `README.md`                      | Documentation file for the Power BI dashboard project            |

---

## 🎯 Objectives

- Visualize overall YTD and QTD sales and product-level metrics.
- Identify top-performing and underperforming product categories.
- Analyze customer engagement via review data.
- Understand sales trends by month and week to optimize marketing.
- Deliver insights that support data-driven product and campaign decisions.

---

## 🛠️ Tools Used

- **Power BI Desktop**
- **Microsoft Excel (CSV cleaning)**
- **Power Query (for minor transformations)**

---

## ✅ Step-by-Step Procedure

### 🔹 Step 1: Data Import & Cleaning
- File used: `amazon_sales_data.csv`
- Actions performed:
  - Verified data types (dates, numbers)
  - Removed null values and unnecessary columns
  - Created calculated fields like QTD/YTD
  - Normalized product categories

### 🔹 Step 2: Power BI Dashboard Creation
- Visuals Included:
  - **KPI Cards**: YTD Sales, QTD Sales, Product Count, Review Volume
  - **Sales by Month & Week**: Time series for trend spotting
  - **Sales by Product Category**: Matrix table with % share
  - **Top Products by Sales and Reviews**: Horizontal bar charts
  - **Interactive Filters**: Category and Quarter

---

## 🔍 Key Insights

🟢 **Top Category**:  
- Men Shoes: **$940K** – **43.18%** of YTD sales

🟢 **Top Products by Sales**:  
- Nikon WiFi Camera – **$34K**  
- Atomos Ninja Recorder – **$28K**

🟢 **Top Products by Reviews**:  
- SanDisk 128GB – **0.40M reviews**  
- SanDisk 1TB SSD – **0.34M reviews**

📈 **Trend Observation**:  
- Sales surge in **September**, **November**, and **December**, suggesting strong Q4 seasonal performance.

🔴 **Underperforming Segments**:  
- Mobile & Accessories – only **1.80%** of sales  
- Toys – minimal revenue despite being present

---

## 📈 Visual Snapshots

Screenshots are available under `dashboard_screenshots/` to view:
- Dashboard Overview
- Product Category Breakdown
- Top Product Sales & Reviews

---

## 🔁 How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-product-sales-dashboard.git
   cd amazon-product-sales-dashboard
2. Open Amazon_Products_Dashboard.pbix in Power BI Desktop.

3. Interact with slicers and visuals to explore insights.

🔄 Workflow Summary

This project follows the Power BI development process:

Data Import → Transformation → Visualization → Insight Derivation

Final Dashboard → Export → Storytelling with Data

