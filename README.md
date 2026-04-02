# Olist Brazilian E-Commerce Dashboard

## Live Dashboard
🔗 [View Interactive Dashboard](https://public.tableau.com/app/profile/sushma.evs/viz/tableau_dashboard_v1/Dashboard1)

## Overview
End-to-end data analytics project on the Olist Brazilian E-Commerce 
dataset from Kaggle. Covers data cleaning, feature engineering, 
exploratory analysis, and an interactive Tableau dashboard.

## Key Metrics
| Metric | Value |
|---|---|
| Total Orders | 96,414 |
| Total Revenue | $15,406,516 |
| Avg Order Value | $159.80 |
| Avg Delivery Time | 12.0 days |
| On-time Delivery Rate | 93.3% |
| Avg Review Score | 4.1 / 5 |
| NPS Proxy Score | 38.2 |
| Repeat Customer Rate | 6.1% |

## Dashboard Components
- **Executive Header** — summary stats at a glance
- **4 KPI Tiles** — orders, revenue, delivery, satisfaction
- **Orders Over Time** — monthly growth trend Jan 2017 to Aug 2018
- **Revenue by State** — top 10 Brazilian states by revenue
- **Business Health Scorecard** — 5 operational metrics
- **Top 5 Categories** — highest revenue product categories

## Key Insights
- São Paulo drives 43% of all orders
- Health & Beauty is the top category at R$1.26M revenue
- 73.9% of customers prefer credit card with avg 3.7 installments
- Amazon region delivery is 3x slower than São Paulo (28.7d vs 8.3d)
- 93.9% one-time buyers — significant retention opportunity

## Tech Stack
| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning & feature engineering |
| Matplotlib, Seaborn | Exploratory data analysis |
| Tableau | Interactive dashboard |

## Dataset
Brazilian E-Commerce Public Dataset by Olist — available on 
[Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- 9 relational CSV files merged into one flat fact table
- 96,414 delivered orders
- Jan 2017 to Aug 2018
- 27 Brazilian states
- 72 product categories
- 3,095 active sellers

## Data Pipeline
```
9 raw CSVs → merge & clean in Python → feature engineering → EDA → Tableau dashboard
```
