# Banking Customer Analytics Dashboard

## Overview
This project presents an end-to-end data analytics workflow using a banking customer dataset. The objective is to analyze customer financial behavior, risk exposure, and product engagement, and to present insights through a professional, interactive Power BI dashboard.

The project demonstrates the complete analytics lifecycle — from data cleaning and exploratory data analysis (EDA) in Python to dashboard design and storytelling in Power BI.

---

## Objectives
- Understand customer income, assets, liabilities, and risk profiles
- Analyze customer tenure and loyalty patterns
- Identify relationships between net worth and risk exposure
- Compare assets vs liabilities across customer segments
- Visualize product engagement across banking services

---

## Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn) – Data cleaning & EDA  
- **Jupyter Notebook** – Exploratory analysis and feature engineering  
- **Power BI** – Interactive dashboard development  
- **GitHub** – Version control and portfolio hosting  

---

## Dataset
The dataset contains customer-level banking information including:
- Demographics (age, location, tenure)
- Financial metrics (income, assets, liabilities)
- Risk indicators
- Banking product balances
- Loyalty classification

---

## Exploratory Data Analysis (EDA)
EDA was performed in Python to:
- Inspect data structure and data quality
- Convert date fields and derive customer tenure
- Analyze distributions of income, tenure, and financial variables
- Explore relationships between risk, net worth, and liabilities
- Engineer features such as total assets, total liabilities, and net worth

The cleaned and processed dataset was exported for use in Power BI.

📁 Notebook: `EDA/Banking_Dataset_EDA.ipynb`

---

## Power BI Dashboard
An interactive, one-page Power BI dashboard was created to present insights in a clear and business-focused manner.

### Dashboard Highlights:
- **Executive KPIs**: Average income, net worth, assets, liabilities, risk, and tenure
- **Customer Distributions**: Income bands and tenure groups
- **Risk Analysis**: Relationship between customer risk and net worth
- **Comparisons**: Assets vs liabilities by segment
- **Product Engagement**: Average balances across banking products

📁 Files:
- `Banking_Customer_Dashboard.pbix`
- `Banking_Customer_Dashboard.pdf`
- `Banking.csv`
- `EDA_BankingDataset.ipynb`
---

## Key Insights
- Average customer net worth is negative, driven by higher loan exposure
- Risk levels vary significantly across net worth and tenure segments
- Assets and liabilities differ notably by income band
- Certain banking products dominate customer financial exposure
- Longer-tenured and higher-income customers tend to show healthier financial profiles
