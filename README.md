# 📊 Customer Churn Analysis
Customer churn analysis using Python, Pandas, SQLite and data visualization

## 📌 Project Overview
This project focuses on analyzing customer churn to understand why customers discontinue their subscriptions and to identify patterns related to customer retention.

The project uses Python, SQL, and data visualization techniques to clean, transform, analyze, and visualize customer subscription and support data.

## 🎯 Objectives
- Perform data cleaning and preprocessing.
- Combine customer, subscription, and support datasets.
- Calculate customer churn and retention rates.
- Analyze churn across different subscription plans.
- Explore customer lifetime value (CLTV) and monthly charges.
- Analyze customer support escalations and their relationship with churn.
- Create visualizations to identify trends and patterns.

## 🛠️ Tools & Technologies
- **Python** — Data analysis
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations and feature engineering
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **SQLite** — Data storage and SQL queries
- **Jupyter Notebook** — Development environment

## 🔄 Project Workflow
1. Extract data from SQLite tables.
2. Inspect datasets and identify missing values.
3. Clean and standardize customer information.
4. Convert columns to appropriate data types.
5. Merge customer, subscription, and support datasets.
6. Create features such as churn flags and churn-risk categories.
7. Perform exploratory data analysis (EDA).
8. Visualize churn patterns and interpret the results.

## 📈 Key Findings
Based on the current sample dataset:

- **Churn Rate:** 28.57%
- **Retention Rate:** 71.43%
- **Average Monthly Charges:** 18.85 currency units
- **Escalation–Churn Correlation:** Approximately 0.77

The Basic subscription plan showed a higher churn rate than the Standard and Premium plans in this sample.

These findings are exploratory and should be interpreted cautiously because the dataset contains only 21 customers.

## 📊 Visualizations
The project includes visualizations such as:
- Monthly churn trend
- Churn by subscription plan
- Churn by state
- Correlation analysis between selected variables

## 📂 Project Files
- `customer_churn_analysis.ipynb` — Jupyter Notebook containing the analysis and visualizations.
- `Churn_analysis.pdf` — Project report.
- `exported_churn_data.csv` — Cleaned dataset

## 🚀 Future Improvements
- Analyze a larger customer dataset.
- Build an interactive dashboard using Power BI or Tableau.
- Develop a machine-learning model for churn prediction.
- Identify actionable strategies to improve customer retention.

