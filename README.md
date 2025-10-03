📊 Credit Card Data Analysis using SQL Server & Power BI

This project demonstrates how raw customer and credit card transaction data can be transformed into business insights using SQL Server for data ingestion & cleaning, and Power BI for interactive dashboarding.
The pipeline covers the complete workflow:

1-Import CSV datasets into SQL Server.
2-Clean and handle data mismatches (date formats, numeric conversions, schema issues).
3-Connect SQL Server to Power BI for modeling and visualizations.
4-Build dashboards to analyze revenue, transactions, card usage, and customer demographics.

📂 Repository Contents

1-credit_card.csv → Raw credit card transaction dataset.
2-customer.csv → Customer demographic dataset.
3-report.pdf → Power BI dashboards exported as PDF.
4-credit_card_insight.pdf → Clean insights summary report.

🛠️ Tech Stack

1-SQL Server – Data import, staging, cleaning, and relational modeling.
2-Power BI Desktop – Dashboard design and data visualization.
3-CSV Files – Raw input data.
4-DAX & SQL Queries – Used for calculations and transformations.

🚀 Steps to Reproduce

1-Load credit_card.csv and customer.csv into SQL Server using BULK INSERT or SSMS Import Wizard.
2-Handle datatype issues by first inserting into staging tables (all VARCHAR), then casting into correct datatypes.
3-Connect Power BI to SQL Server (cc_details table).
4-Build dashboards with charts for revenue, transactions, customer insights.
5-Export the report (example included in report.pdf).

📊 Key Insights

-Quarterly Revenue → Q2 shows peak revenue and transactions. 

-Top Spending Categories → Bills & Entertainment dominate, followed by Grocery, Travel, and Fuel.
-Customer Segments → Graduates & Businessmen contribute highest revenue.
-Card Category → Blue cards dominate both revenue & usage.
[credit_card_](dashboard.png)
[Customer_Trascation](dashboard2.png)
-Channel Analysis → Swipe transactions are most common, followed by Chip and Online.
-Age & Income Trends → Older and higher-income customers spend more.

✅ Conclusion

This project demonstrates how raw CSV datasets can be transformed into actionable insights through SQL Server cleaning & Power BI dashboards. It is a practical reference for learning data pipelines, ETL, and business analytics.
