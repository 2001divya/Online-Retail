User Retention Cohort Analysis
Tools: Python · Pandas · Matplotlib · Seaborn  
Dataset: UCI Online Retail Dataset (541,909 transactions)  
Domain: Product Analytics / E-commerce

Business Question
After a customer makes their first purchase, do they come back?  
This project analyzes one full year of real e-commerce transaction data 
to measure customer retention across monthly cohorts.

Dataset
Source: UCI Machine Learning Repository — Online Retail Dataset
Period: December 2010 – December 2011
Size: 541,909 transactions, 4,338 unique customers (after cleaning)

Methodology
1. Data Cleaning — removed missing CustomerIDs, invalid quantities/prices
2. Feature Engineering — created Revenue, InvoiceMonth, CohortMonth columns
3. Cohort Analysis — tracked each monthly cohort across 13 months
4. Visualization — heatmap and bar chart of retention rates

Key Findings
1. Average Month-1 Retention: 20.62% — 4 in 5 customers never return
2. Strongest Cohort: Dec 2010 (36.6%) — likely driven by Christmas season
3. Weakest Cohort: Nov 2011 (11.1%) — sharp acquisition quality drop
4. Retention stabilizes at 20–25% from Month 2 onwards

Recommendation
Focus re-engagement efforts within the first 30 days of acquisition — 
that's where 80% of customers are lost.

How to Run
1. Clone this repository
2. Place `Online Retail.xlsx` in the project folder or add appropriate path
3. Run `Analysis Online Retail.ipynb` in Jupyter or VS Code
