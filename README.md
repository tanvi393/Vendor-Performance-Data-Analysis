# 🧾 Vendor Performance Data Analysis (SQL + Python + Power BI)

## 📘 Project Overview
This project focuses on **analyzing vendor performance data** to uncover insights related to profitability, pricing strategies, inventory turnover, and procurement efficiency.  
Using **SQL, Python, and Power BI**, a full **Exploratory Data Analysis (EDA)** was performed to detect anomalies, optimize pricing, and design a data-driven vendor evaluation framework.

---

## 🧩 Objectives
- Understand vendor-wise sales, profit, and purchase behavior.
- Identify inefficiencies in pricing, freight, and stock management.
- Evaluate vendor dependency in procurement and bulk-buying effects.
- Build an **interactive Power BI dashboard** for decision-makers.
- Provide actionable insights for procurement and vendor relationship optimization.

---

## ⚙️ Tech Stack
| Tool / Language | Purpose |
|------------------|----------|
| **SQL** | Data extraction, cleaning, and aggregation |
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | EDA, outlier detection, statistical analysis |
| **Power BI** | Dashboard creation and KPI visualization |
| **Excel / CSV** | Raw data source |
| **Git & GitHub** | Version control and project management |

---

## 🧮 Key Analysis Steps

### 1. Data Understanding & Preparation
- Merged multiple vendor-related tables to create a consolidated dataset.
- Checked data quality, missing values, and distribution of key variables.
- Verified column relationships to determine metrics relevant for reporting.

### 2. Exploratory Data Analysis (EDA)
- Calculated **summary statistics** to detect negative and zero values.
- Identified outliers in **freight cost, purchase price, and stock turnover**.
- Used correlation analysis to understand relationships between:
  - Purchase Quantity vs. Sales Quantity (strong positive correlation)
  - Profit Margin vs. Sales Price (negative correlation)
  - Stock Turnover vs. Gross Profit (weak negative correlation)

### 3. Business Insights
- **Bulk Purchases:** Vendors purchasing in large volumes experienced a **~72% reduction in unit price**, showing the effectiveness of bulk-buying incentives.  
- **Freight & Stock Inefficiencies:** High freight variability (0.09–257,032) and inconsistent stock turnover indicate areas for logistics optimization.  
- **Profitability Pattern:** Vendors with lower sales volumes maintained higher profit margins, suggesting premium pricing or niche product positioning.  
- **Procurement Dependence:** Top vendors accounted for a major share of total purchases, emphasizing the need for diversification.  
- **Hypothesis Testing:** Conducted t-test to confirm significant difference in profit margins between top and low-performing vendors.

---

## 📊 Power BI Dashboard Features
- Vendor-wise and brand-wise performance KPIs  
- Interactive slicers for filtering by product, region, or time  
- Visuals for:
  - Profit vs. Sales distribution  
  - Inventory turnover rates  
  - Procurement dependency ratios  
  - Confidence intervals of profit margins  
- Executive summary page highlighting actionable business recommendations



---

## 🧠 Insights & Recommendations
- **Optimize Bulk Pricing:** Continue incentivizing large-volume purchases to sustain cost advantages.  
- **Improve Freight Efficiency:** Investigate extreme freight cost variations to reduce logistics waste.  
- **Revise Pricing Strategies:** High-margin, low-sales vendors should explore promotional adjustments or bundling.  
- **Diversify Vendors:** Reduce dependency on top contributors to mitigate supply-chain risks.  
- **Monitor Inventory Turnover:** Identify slow-moving stock and reallocate resources effectively.

---
