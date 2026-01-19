UK Cost of Living Analysis – Research Analyst Portfolio

Dataset: Kaggle “Global Cost of Living”
Focus: Customer vulnerability in the UK housing market
Tools: Pandas (for data loading), SQLite (for SQL queries)

Research Question:

Which UK cities are most financially vulnerable for residents, based on cost of living and local purchasing power?

This analysis helps SNG identify areas where residents might struggle to afford housing, groceries, and daily expenses. The goal is to provide actionable insights that can guide support programs and customer-focused interventions.

Project Overview:

This project analyses UK cities using cost of living indices, rent, groceries, and local purchasing power. It highlights vulnerable areas where financial stress is likely higher. SQL queries are used to calculate and rank vulnerability scores, providing clear, data-driven insights.

Methodology:

Filter UK cities: Only rows with country == 'United Kingdom' were used.

Clean and prepare data: Columns renamed for clarity, and missing values (NaN) replaced with 0.

Load data into SQLite: An in-memory SQLite database was used to run SQL queries.

Run SQL queries to identify:

Top 10 cost of living cities

Top 10 rent index cities

Top 10 grocery cost cities

Most financially vulnerable cities (Vulnerability Score = Cost of Living ÷ Local Purchasing Power)

Combined cost pressure score (weighted sum of cost, rent, and groceries)

Key Insights:

Many UK cities have low local purchasing power (0–7.21), making even moderate costs impactful.

Cities with the highest vulnerability scores are where costs outweigh local purchasing power the most.

These insights can help SNG prioritize support in areas where customers may be financially stressed.

Skills Demonstrated:

SQL querying and database management (SQLite)

Data cleaning and NaN handling with Pandas

Quantitative research and insight generation

Translating complex data into actionable business recommendations
