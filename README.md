# Blinkit Grocery Analytics Dashboard

An end‑to‑end analytics solution built on Blinkit’s grocery transaction data to uncover sales trends, customer behavior and operational insights.

## 🚀 Project Overview
- **Data Cleaning & Modeling**  
  Raw transaction and product tables were ingested into a PostgreSQL database. Using SQL scripts, data were cleaned, deduplicated and joined into a star‑schema model optimized for reporting.

- **Exploratory Analysis**  
  Leveraged Python (pandas, numpy, matplotlib) to:
  - Profile key metrics (daily sales, average basket size, product mix)  
  - Identify seasonality, outliers and correlation between spend categories  
  - Generate static charts and summary tables for ad‑hoc analysis

- **Interactive Dashboard**  
  Built in **Power BI**, this dashboard features:  
  - KPI cards for total sales, average order value, and repeat purchase rate  
  - Time‑series and bar charts to compare performance by week, state and product category  
  - Slicers for dynamic filtering by date range, geography and customer segment  
  - Drill‑through reports to inspect granular order‑level details

## 🛠 Tech Stack
- **Database & ETL:** PostgreSQL, SQL  
- **Analysis & Visualization:** Python (pandas, numpy, matplotlib)  
- **Dashboarding:** Microsoft Power BI  
- **Data Source:** `BlinkIT Grocery Data.xlsx`
