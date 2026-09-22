# bank-customer-churn-powerbi

# Bank Customer Churn Analysis Dashboard

## Business Problem
Banks lose significant revenue when customers close their accounts (churn). This project 
analyzes 10,000 bank customers to identify which segments are most likely to churn, so the 
business can prioritize retention efforts where they matter most.

## Objective
Build an interactive Power BI dashboard that helps a retention team answer:
- What is our overall churn rate, and is it a problem?
- Which customer segments (age, gender, geography, balance, product count) churn the most?
- Where should retention budget be focused first?



## Tools & Approach
- **Data:** Churn_Modelling.csv (10,000 customer records: age, balance, tenure, credit score, 
  geography, gender, product count, active status, exited flag)
- **Tools:** Power BI (data modeling, DAX measures, interactive slicers/filters)
- **Approach:** Cleaned and loaded the dataset into Power BI, built KPI cards for headline 
  metrics, then broke down churn by gender, age bin, balance range, geography, and product 
  count to surface patterns — with Gender and Geography filters for interactive exploration.

## Key Metrics
- Total Customers: 10,000 | Total Exited: 2,000 (**20% overall churn rate**)
- Average Age: 38.92 | Average Balance: 76.49K | Average Tenure: 5.01 years
- Average Credit Score: 650.53 | Active Members: 5,000 | Credit Card Holders: 7,000

## Key Findings
- **Gender:** Female customers churned at a higher rate (55.92%) than male customers (44.08%) — 
  a meaningful gap worth investigating further (service experience, product fit, etc.)
- **Age:** Churn rises sharply with age. Younger customers (20s) are highly loyal, while the 
  51+ age bracket shows dramatically higher exit rates.
- **Balance:** Customers with higher balances (0.1M–0.2M range) churn more than low-balance 
  customers — counterintuitive, and worth a closer look at what's driving high-value customers away.
- **Products:** Customers holding 2 products behave differently from those with 1, suggesting 
  product engagement plays a role in retention.
- **Geography:** Churn varies by country, explorable via the dashboard filter.

## Business Recommendation
Retention efforts should prioritize older, higher-balance female customers, as this segment 
shows the compounding highest churn risk. A targeted outreach or loyalty program for this group 
could reduce overall churn more efficiently than a blanket retention campaign.


2. Open it in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) (free)
3. Use the Gender and Geography filters on the right to slice the data
