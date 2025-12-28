# fintech-transaction-analytics
End-to-end fintech data analytics project using SQL, Python, and MySQL to analyze transaction growth, user adoption, and engagement trends.
## Overview
This project analyzes aggregated digital payment transaction data to understand user adoption, transaction growth, and engagement trends in a fintech context. The analysis focuses on identifying growth drivers, seasonality patterns, and market concentration using SQL and Python.

## Data
The dataset consists of aggregated fintech transaction and user metrics across multiple years and quarters, segmented by transaction type, geographic region (state), and device brand. The data was cleaned and processed before analysis and loaded into a MySQL database for querying.

## Business Questions
- How has total transaction value evolved?
- How has user adoption changed across years?
- Is growth driven by new users or increased engagement per user?
- Which transaction types and regions drove peak performance?
- Are there seasonal patterns in transaction activity?

## Key Insights
- Total transaction value increased steadily from 2018 to 2021, peaking in 2021, followed by a decline in 2022, indicating rapid fintech adoption during this period and a subsequent normalization phase.
- User adoption closely mirrored transaction growth, suggesting that overall platform performance was primarily driven by increases in the user base rather than isolated spending spikes.
- Transaction value per user increased through 2021, highlighting rising user engagement alongside adoption growth.
- Peer-to-peer payments accounted for the majority of transaction value during the 2021 peak, identifying them as the primary driver of platform growth.
- Transaction activity was geographically concentrated, with a small number of states contributing a significant share of total transaction value, indicating both growth hubs and concentration risk.
- Strong seasonality was observed across all years, with Q4 consistently generating the highest transaction volumes.

## Tools & Skills Used
- SQL (MySQL, CTEs, window functions, aggregations)
- Python (Pandas, Matplotlib, Seaborn)
- MySQL Workbench
- Data cleaning and feature engineering
- Exploratory data analysis
- Business insight communication

## How to Run
1. Load the cleaned CSV files into a MySQL database.
2. Execute SQL queries to generate KPIs and aggregated metrics.
3. Use the provided Jupyter notebook to perform exploratory analysis and generate visualizations.
