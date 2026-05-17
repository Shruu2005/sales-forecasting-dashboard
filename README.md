# 📈 Sales Forecasting & Business Performance Dashboard

> An end-to-end Data Science project analyzing 3 years of sales data across 4 regions and 5 categories, with 6-month future forecasting and an interactive business dashboard.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![ScikitLearn](https://img.shields.io/badge/ScikitLearn-Forecasting-orange?style=flat&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 📌 Project Overview

This project builds a **Sales Forecasting & Business Performance Dashboard** that:
- Analyzes 3 years (2021–2023) of sales data — 720 records across 4 regions & 5 categories
- Performs Exploratory Data Analysis (EDA) with 7 visual charts
- Forecasts **next 6 months sales** using Polynomial Regression (R²=0.712)
- Identifies seasonal trends, regional performance & category insights
- Presents everything in a **dark-themed interactive HTML dashboard**

---

## 🗂️ Project Structure

```
sales-forecasting-dashboard/
│
├── sales_data.csv            # Dataset — 720 records, 13 features
├── sales_dashboard.html      # Interactive dashboard (open in browser)
├── sales_eda.png             # EDA visualizations (7 charts)
├── sales_forecast.png        # Forecast chart with trend line
└── README.md                 # Project documentation
```

---

## 📊 Dataset Features

| Feature | Description |
|---|---|
| Date | Month-Year of sales record |
| Year / Month | Year and month number |
| Quarter | Q1 / Q2 / Q3 / Q4 |
| Region | North / South / East / West |
| Category | Electronics / Clothing / Furniture / Groceries / Sports |
| Sales_INR | Total sales in Indian Rupees |
| Units_Sold | Number of units sold |
| Profit_INR | Profit earned |
| Discount_pct | Discount percentage applied |
| Returns | Number of returned units |
| **Profit_Margin_pct** | **Profit as % of Sales** |

---

## 🔍 EDA Highlights

![EDA Report](sales_eda.png)

Key findings from Exploratory Data Analysis:
- **Total Revenue: ₹8.99 Cr** across 3 years (2021–2023)
- **Total Profit: ₹2.37 Cr** with avg margin of **26.4%**
- **North Region** leads with **29.7% share** of total sales
- **Electronics** is the top category at **₹23.91L** total revenue
- **Consistent 8% YoY growth** from 2021 to 2023
- **November–December** are peak months (Electronics festive season)

---

## 🔮 Sales Forecast

![Forecast](sales_forecast.png)

6-Month Forecast using **Polynomial Regression**:

| Month | Forecasted Sales |
|---|---|
| January 2024 | ₹28.15L |
| February 2024 | ₹28.33L |
| March 2024 | ₹28.50L |
| April 2024 | ₹28.68L |
| May 2024 | ₹28.86L |
| June 2024 | ₹29.04L |

> 📌 Model: Polynomial Regression (Degree 2) · R² Score: 0.712 · MAE: ₹91.1K

---

## 📈 Interactive Dashboard

Open `sales_dashboard.html` in any browser — no installation needed!

**Dashboard Tabs:**
- 📊 **Overview** — KPI cards, monthly trend, region pie, quarterly comparison
- 🗺️ **Regions** — Region-wise performance, trend lines, year comparison
- 📦 **Categories** — Category sales, profit margins, seasonal patterns
- 🔮 **Forecast** — 6-month prediction, trend line, growth scenario simulator
- 📋 **Details** — Filterable sales records table

---



## ⚙️ How to Run

### 1. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2. Run EDA Script
```bash
python eda_sales.py
```

### 3. Open Dashboard
```bash
# Just open in your browser
open sales_dashboard.html
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.10+ | Core programming |
| Pandas & NumPy | Data processing & EDA |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Polynomial Regression forecasting |
| HTML / CSS / JS / Chart.js | Interactive dashboard |

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---


