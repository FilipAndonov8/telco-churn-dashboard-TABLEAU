# Customer Churn Rate Dashboard — Tableau

🔗 **[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/filip.andonov/viz/ChurnRateDashboard_17713481108880/CHURNRATEDASHBOARD)**

## Overview
This project analyzes customer churn for a telecom company using the well-known Telco Customer Churn dataset. The dashboard identifies which customer segments are most likely to cancel their service, helping a business prioritize retention efforts where they'll have the most impact.

## Dataset
- **`Telco-Customer-Churn.csv`** — 7,043 customer records with 21 fields covering demographics (gender, senior citizen status, dependents), account details (tenure, contract type, payment method), services subscribed (internet, phone, streaming, tech support, etc.), billing (monthly/total charges), and churn status (Yes/No)

## Tools Used
- **Tableau** — interactive churn rate dashboard

## Key Insights
- **Overall churn rate is 26.5%** — roughly 1 in 4 customers cancel their service, representing about $139,000 in lost monthly recurring revenue.
- **Contract type is the single biggest driver of churn**: month-to-month customers churn at 42.7%, compared to just 11.3% for one-year contracts and 2.8% for two-year contracts. This points to a clear retention strategy — incentivizing customers to move from month-to-month to longer-term contracts could dramatically reduce churn.
- **New customers are the highest risk**: customers in their first 12 months churn at 47.7%, dropping to 9.5% for customers with 49-72 months of tenure. Churned customers average just 18 months of tenure vs. 37.6 months for retained customers — the first year is the critical retention window.
- **Fiber optic internet customers churn at more than double the rate of DSL customers** (41.9% vs. 19.0%), despite presumably being a premium service — this could point to pricing, reliability, or competition issues specific to fiber customers worth investigating further.
- **Electronic check users churn at 45.3%**, far higher than automatic payment methods (bank transfer 16.7%, credit card 15.2%) — encouraging migration to automatic payments could be a simple, low-cost retention lever.
- **Lack of tech support correlates strongly with churn**: customers without Tech Support churn at 41.6%, vs. 15.2% for those who have it — suggesting that bundling or upselling support services could improve retention.
- **Senior citizens churn at nearly double the rate of non-seniors** (41.7% vs. 23.6%), and churned customers pay higher average monthly charges ($74.44 vs. $61.27) — suggesting price sensitivity may be a factor for at-risk segments.

## How to Use
1. View the live interactive dashboard via the [Tableau Public link](https://public.tableau.com/app/profile/filip.andonov/viz/ChurnRateDashboard_17713481108880/CHURNRATEDASHBOARD) above
2. Or open the workbook in Tableau Desktop/Public, connected to `data/Telco-Customer-Churn.csv`
