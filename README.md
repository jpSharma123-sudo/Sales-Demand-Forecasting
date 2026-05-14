# 📈 Time-Series Analysis of Sales & Demand Forecasting

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Statsmodels](https://img.shields.io/badge/Statsmodels-SARIMA-purple?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

---

## 🗂️ Project Overview

A professional end-to-end Data Science project focused on **Time-Series Analysis** and **Sales Demand Forecasting** using the Kaggle Monthly Sales Dataset (2003–2005). This project covers full exploratory data analysis, time-series decomposition, SARIMA modeling, and 6-month forward forecasting — built for internship submissions and portfolio presentations.

---

## 📁 Project Structure

```
Time-Series Analysis of Sales and Demand Forecasting/
│
├── 📄 README.md                          # Project overview & instructions
│
├── 📁 01_Dataset/
│   └── sales_data_sample.csv             # Raw dataset (Kaggle)
│
├── 📁 02_Notebook/
│   └── Sales_Forecasting.ipynb           # Main Jupyter Notebook
│
├── 📁 03_Report/
│   └── Sales_Forecasting_Report.pdf
│
├── 📁 04_Visualizations/
│   ├── Fig1_EDA_Overview.png
│   ├── Fig2_Trend_Analysis.png
│   ├── Fig3_Seasonality_Analysis.png
│   ├── Fig4_Decomposition.png
│   ├── Fig5_SARIMA_Validation.png
│   ├── Fig6_Future_Forecast.png
│   └── Fig7_Rolling_Average.png
│
└── 📁 05_Requirements/
    └── requirements.txt                  # Python dependencies
```

---

## 🚀 Getting Started

**Step 1 — Install dependencies:**

```bash
pip install -r 05_Requirements/requirements.txt
```

**Step 2 — Open the notebook:**

```bash
cd 02_Notebook
jupyter notebook Sales_Forecasting.ipynb
```

**Step 3 — Run all cells:**

```
Kernel → Restart & Run All
```

---

## 🧰 Tech Stack

| Library | Version | Purpose |
|---|---|---|
| `pandas` | 2.2.2 | Data manipulation & time-series aggregation |
| `numpy` | 1.26.4 | Numerical operations |
| `matplotlib` | 3.8.4 | Low-level plotting |
| `seaborn` | 0.13.2 | Statistical visualizations |
| `statsmodels` | 0.14.2 | SARIMA modeling & decomposition |
| `scikit-learn` | 1.4.2 | Accuracy metrics (MAE, RMSE, MAPE) |

---

## 🔍 Project Sections

1. **Project Introduction** — Scope, objectives, and dataset overview
2. **Dataset Loading** — Import with encoding handling
3. **Data Cleaning** — Nulls, duplicates, and type fixes
4. **Datetime Conversion** — Datetime indexing for time-series
5. **Exploratory Data Analysis** — Distribution, product lines, and geography
6. **Trend Analysis** — Long-term growth and year-over-year comparison
7. **Seasonality Analysis** — Monthly heatmap and quarterly cycles
8. **Monthly Sales Visualization** — Revenue time series with annotations
9. **Rolling Average Analysis** — 3-month, 6-month, and 12-month smoothing
10. **Time-Series Decomposition** — Trend, Seasonal, and Residual (Additive Model)
11. **SARIMA Forecasting** — SARIMA(1,1,1)(1,1,1,12) with train/test split
12. **Forecast Accuracy Metrics** — MAE, RMSE, and MAPE evaluation
13. **Future Sales Prediction** — 6-month forward forecast with 95% confidence intervals
14. **Business Insights** — Actionable findings for stakeholders
15. **Conclusion** — Summary and model performance

---

## 📊 Key Results

| Metric | Value |
|---|---|
| Total Revenue (2003-2005) | 10 Million approx |
| Total Orders | 2,823 |
| Peak Month | November 2004 |
| Best Quarter | Q4 (Oct-Dec) |
| Q4 Revenue Share | 40% of annual total |
| Top Product Line | Classic Vehicles |
| Top Country | USA |
| SARIMA MAE | 56,600 approx |
| SARIMA RMSE | 70,000 approx |
| SARIMA MAPE | 14.6% |
| Forecast Horizon | 6 Months |
| Nov 2005 Forecast | 1.36 Million approx |

---

## 💼 Business Insights

- **Q4 dominates** — 40% of annual revenue is concentrated in October to December
- **November peak** — consistently the highest revenue month every year
- **Classic Vehicles** — top revenue-generating product line across all years
- **USA is the No.1 market** — contributes over 35% of global sales
- **Strong YoY growth** — significant revenue increase from 2003 to 2004
- **SARIMA forecast** — projects continued seasonal growth in the upcoming Q4 cycle

---

## 👤 Author


**Jaiprakash Sharma**
Tools: Python · Jupyter · Pandas · Statsmodels · Seaborn · SARIMA
Dataset: [Kaggle — Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

---

