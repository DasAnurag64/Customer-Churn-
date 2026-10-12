# 📦 Boxify Customer Churn Analysis & Retention Dashboard

An end-to-end data analytics project evaluating customer churn dynamics for **Boxify**, a direct-to-consumer (D2C) subscription platform. This project blends Python data manipulation, statistical analysis, and interactive Power BI business intelligence reporting to identify churn drivers, calculate revenue loss, and prescribe retention strategies.

---

## 📌 Executive Summary

Customer acquisition costs are significantly higher than retention costs in recurring subscription business models. For Boxify, involuntary churn and drop-offs following onboarding incentives pose recurring revenue risks.

This project delivers:
- **Comprehensive Data Audit:** Cleaning, preprocessing, and engineering interaction and engagement metrics.
- **Root Cause Diagnostics:** Statistical and visual breakdown of churn across contract lengths, payment methods, customer service contacts, and subscription tiers.
- **Interactive Business Intelligence:** Power BI dashboard featuring dynamic DAX measures tracking churn rates, cohort survival, and Monthly Recurring Revenue (MRR) impact.
- **Strategic Recommendations:** Targeted retention interventions designed to minimize churn in at-risk cohorts.

---

## 🛠️ Tech Stack & Tools

| Domain | Technology / Library | Usage |
| :--- | :--- | :--- |
| **Language** | Python (3.9+) | Data cleaning, feature engineering, exploratory data analysis |
| **Data Processing** | `pandas`, `numpy` | Tabular data wrangling, missing value treatment, aggregations |
| **Data Visualization** | `matplotlib`, `seaborn` | Statistical distributions, heatmaps, correlation analysis |
| **Business Intelligence** | Microsoft Power BI & DAX | Dynamic interactive dashboard, KPI cards, retention matrices |
| **Version Control** | Git & GitHub | Source tracking, modular scripts, documentation |

---

## 📂 Project Architecture

```text
boxify-churn-analysis/
│
├── data/
│   ├── raw/
│   │   └── boxify_customer_data_raw.csv        # Raw transaction & customer dataset
│   └── processed/
│       └── boxify_cleaned_churn_data.csv       # Preprocessed and engineered dataset
│
├── notebooks/
│   ├── 01_data_cleaning_and_profiling.ipynb    # Handling nulls, outliers, data types
│   ├── 02_exploratory_data_analysis.ipynb      # Bivariate & multivariate analysis
│   └── 03_cohort_and_churn_metrics.ipynb       # Tenure analysis and engagement scoring
│
├── power_bi/
│   ├── boxify_churn_dashboard.pbix             # Power BI dashboard report file
│   └── dashboard_screenshots/                 # Dashboard previews and visuals
│
├── dax/
│   └── measures.dax                            # Extracted DAX calculation scripts
│
├── requirements.txt                            # Python environment dependencies
├── LICENSE                                     # Open-source license
└── README.md                                   # Project documentation
