# Fintech Transaction Analytics

End-to-end fintech data analytics project using SQL, Python, and MySQL to analyze
transaction growth, user adoption, engagement trends, and market concentration.

---

## Overview
This project analyzes aggregated digital payment transaction data to understand
user adoption, transaction growth, and engagement patterns in a fintech context.
The analysis focuses on identifying growth drivers, seasonality effects, and
geographic concentration using SQL and Python.

---

## Data
The dataset consists of aggregated fintech transaction and user metrics across
multiple years and quarters, segmented by:
- Transaction type
- Geographic region (state)
- Device brand

The data was cleaned, feature-engineered, and loaded into a MySQL database
to simulate a real-world analytics workflow.

---

## Business Questions
- How has total transaction value evolved over time?
- How has user adoption changed across years?
- Is growth driven by new users or increased engagement per user?
- Which transaction types and regions drove peak performance?
- Are there seasonal patterns in transaction activity?

---

## Key Insights
- Total transaction value increased steadily from 2018 to 2021, peaking in 2021,
  followed by a decline in 2022, indicating rapid fintech adoption and a
  subsequent market normalization phase.
- User adoption closely mirrored transaction growth, suggesting that overall
  platform performance was primarily driven by expansion of the user base.
- Transaction value per user increased through 2021, highlighting rising user
  engagement alongside adoption growth.
- Peer-to-peer payments were the primary driver of transaction value during
  the 2021 peak.
- Transaction activity was geographically concentrated, with a small number of
  states contributing a disproportionate share of total volume, indicating
  growth hubs and concentration risk.
- Strong seasonality was observed across all years, with Q4 consistently
  generating the highest transaction volumes.

---

## Tools & Skills Used
- SQL (MySQL, CTEs, window functions, aggregations)
- Python (Pandas, Matplotlib, Seaborn)
- MySQL Workbench
- Data cleaning and feature engineering
- Exploratory data analysis
- Business insight communication

---

## How to Run
1. Load the cleaned CSV files into a MySQL database.
2. Execute SQL queries to generate KPIs and aggregated metrics.
3. Use the provided Jupyter notebook to perform exploratory analysis and
   generate visualizations.
