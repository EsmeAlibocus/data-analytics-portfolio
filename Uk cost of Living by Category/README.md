# UK Cost of Living by Category (CPIH)

## Project Overview
This project analyses UK cost-of-living trends using category-level Consumer Prices Index including owner occupiers’ housing costs (CPIH) data. The analysis focuses on how different household expenses such as food, housing, transport, and utilities have changed over time, and which categories have contributed most to rising cost-of-living pressures.

The aim of the project is to demonstrate practical business analysis skills using real UK economic data, from data preparation through to insight generation and visualisation.

---

## Data Source
The dataset used in this project is sourced from the Office for National Statistics (ONS):

- **CPIH – Detailed figures by division (Table 2)**

This table provides 12-month percentage changes in prices across major household spending categories, including food, housing and utilities, transport, clothing, and restaurants.

Raw data is stored unchanged in the Under 'Raw Data'

---

## Tools Used
- **Microsoft Excel** – data cleaning, preparation, and feature creation  
- **SQL** – querying, aggregation, and trend analysis  
- **Power BI** – dashboard creation and visualisation  

---

## Data Preparation
The following steps were carried out in Excel:
- Standardised column names and formats
- Created a unified date field from month and year values
- Cleaned and consolidated category names
- Removed metadata and non-data rows
- Added helper columns (year, month number) to support analysis

A cleaned, analysis-ready dataset is stored in the under 'Cleaned Data'.

---

## Analysis Performed
The analysis focuses on understanding cost-of-living changes by category, including:
- Inflation trends over time by household spending category
- Comparison of essential costs such as food, housing, and transport
- Identification of periods with elevated inflation
- Ranking categories by average and latest inflation rates

SQL queries used for the analysis are stored in the `sql` folder.

---

## Key Insights
- Essential household costs such as food and housing showed sustained periods of high inflation
- Transport costs were more volatile compared to other categories
- Cost-of-living pressures were uneven across categories rather than driven by a single expense type

---

## Visualisation
A Power BI dashboard was created to present the findings clearly for non-technical stakeholders.  
The dashboard includes:
- Inflation trends over time by category
- Latest inflation rates by household cost category
- Summary KPIs highlighting key inflation metrics



---

## Project Structure

