# 🇺🇸 USA Regional Sales Analysis

## 🗂️ Project Summary
This project performs an in-depth exploratory data analysis (EDA) on a USA sales dataset. The analysis includes data profiling, cleaning, feature engineering, and visualization to uncover business insights. These insights are presented in an interactive Power BI dashboard to support data-driven decision-making.

---

## ❓ Problem Statement
The goal is to analyze sales data to identify key revenue and profit drivers across products, channels, and regions. The project aims to uncover seasonal trends, outliers, and budget alignment to inform pricing, promotion, and market expansion strategies.

---

## 🎯 Objective

- Identify top-performing products, channels, and regions.
- Uncover seasonal trends and anomalies.
- Spot pricing and margin risks from outlier transactions.
- Provide insights for pricing, promotion, and growth strategies.

---

## 💾 Dataset Description

The dataset originates from an Excel workbook and has been split into the following CSV files:

| File Name                  | Description |
|---------------------------|-------------|
| `Sales Orders.csv`        | Core transactional data for each order. |
| `Customers.csv`           | Customer index mapped to names. |
| `Products.csv`            | Product index mapped to descriptions. |
| `2023 Budgets.csv`        | Budget targets per product for 2023. |
| `Regions.csv`             | State code and geographic information. |
| `State Regions.csv`       | Mapping of states to US regions. |

---

## 🛠️ Tools & Technologies

- **Languages/Libraries**: Python, pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Dashboarding**: Power BI
- **Environment**: Jupyter Notebook

---

## 🔄 Project Workflow

1. **Data Ingestion**  
   Loaded all CSV files into pandas DataFrames.

2. **Data Cleaning & Wrangling**  
   - Merged datasets to form a master DataFrame.  
   - Renamed columns and handled missing values.  
   - Verified data types.

3. **Feature Engineering**  
   - Created `profit`, `total_cost`, and `profit_margin_pct`.

4. **Exploratory Data Analysis (EDA)**  
   - Analyzed revenue, profit, order count, and margins.  
   - Used visualizations to uncover trends and outliers.

5. **Dashboard Development**  
   - Final dataset exported as `Sales_data1(EDA Exported).csv`.  
   - Imported into Power BI for dashboard creation.

---

## 📊 Power BI Dashboard Overview

### 1. Sales Overview
- **KPIs**: Total Revenue, Total Profit, Total Orders, AOV
- **Visuals**: Revenue/Profit by year, heatmaps by month
- **Filters**: Year, Month, Channel, Region

### 2. Product Analysis
- Top products by revenue, profit, and orders
- Profitability matrix (Revenue vs. Profit)

### 3. Customer Analysis
- Top customers by revenue and order count
- Customer performance table with AOV

### 4. Geographical Analysis
- Revenue breakdown by region (pie chart)
- Interactive state-level revenue map
- State-wise performance table

---

## 🔍 Key Findings

- **Channel Mix**: Wholesale leads (54%), with growth opportunity in exports (15%).
- **Top Products**: Product 26 ($118M) and Product 25 ($110M) dominate.
- **Top Region**: California generates ≈$230M in revenue.

---

## 💡 Recommendations

- **Outlier Strategy**: Exclude bulk/promotional SKUs from average metrics.
- **Margin Uplift**: Apply pricing learnings from top performers to others.
- **Export Growth**: Focus on international expansion via distributors.
- **Dashboard Utility**: Use filters to monitor specific time frames or regions.

---

## 📁 Folder Structure

```
📦 USA-Regional-Sales-Analysis
├── data/
│   ├── Sales Orders.csv
│   ├── Customers.csv
│   ├── Products.csv
│   ├── 2023 Budgets.csv
│   ├── Regions.csv
│   └── State Regions.csv
├── notebooks/
│   └── EDA.ipynb
├── exports/
│   └── Sales_data1(EDA Exported).csv
├── dashboard/
│   └── PowerBI_Dashboard.pbix
└── README.md
```

---

## 📬 Contact

For queries or collaboration:  
**Anshuman Saikia**  
📧 `sonowalmonalisha24@gmail.com`  
🔗 *(Add GitHub or LinkedIn if available)*

---
