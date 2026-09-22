# bank-customer-churn-powerbi

# Bank Customer Churn Analysis Dashboard

An interactive Power BI dashboard analyzing churn behavior across 10,000 bank customers, 
built to identify which customer segments are most at risk of leaving.

![Dashboard](dashboard-screenshot.png)

## Tools Used
- Power BI (data modeling, DAX measures, interactive visuals)
- Dataset: Churn_Modelling.csv (10,000 customer records)

## Key Metrics
- **Total Customers:** 10,000
- **Total Exited:** 2,000 (20% overall churn rate)
- **Average Age:** 38.92
- **Average Balance:** 76.49K
- **Average Tenure:** 5.01 years
- **Average Credit Score:** 650.53
- **Active Members:** 5,000
- **Credit Card Holders:** 7,000

## Key Insights
- **Gender:** Female customers exited at a higher rate (55.92%) than male customers (44.08%).
- **Age:** Churn climbs sharply with age — the 60+ segment shows a 100% exit rate in this data, 
  and the 51–60 bracket already shows 56.04% exited, versus under 10% for customers in their 20s.
- **Balance:** Customers with balances in the 0.1M–0.2M range show the highest exit rates 
  (up to 78.25%), compared to lower churn for near-zero balances.
- **Geography:** Exit behavior varies by country (France, Germany, Spain), with filtering 
  available in the dashboard to explore each market.
- **Products:** Customers holding 2 products show a notably different churn pattern than 
  those with 1, highlighting product engagement as a retention factor.

## How to View
This is a Power BI (.pbix) file, which can't be previewed directly in the browser. To explore 
the interactive dashboard yourself:
1. Download `bank-churn-dashboard.pbix` from this repo
2. Open it in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) (free)
3. Use the Gender and Geography filters on the right to slice the data
