Title:
Consumption and Billing Dashboard 📊

Overview:
This project presents a simulated analysis of electricity billing and payment data, designed to reflect typical utility operations. While labeled with real-world references such as Nsawam District and the Electricity Company of Ghana (ECG), all data is entirely fictional and was created for educational and portfolio purposes only.

The goal of the project is to explore key revenue, consumption, and customer behavior metrics using SQL, Excel, and Power BI, mimicking the challenges faced by electricity distribution companies in managing collections, losses, and billing irregularities.

Tools Used:

Excel – For initial visual data cleaning, loss calculation, customer segmentation, trend analysis and structuring

SQL – For data querying

Power BI – For building an interactive and dynamic analytics dashboard

Project Structure:

BillingData Jan-June2025.csv: Cleaned dataset used across SQL and Power BI

sql_queries.sql: SQL queries used to calculate losses, collection rates, customer behavior, and suspicious customers

powerbi_dashboard.pbix: Final Power BI dashboard file

visuals/dashboard_screenshot.png: Screenshot preview of the final dashboard


Dashboard Highlights:

KPI Cards

Total Billed Amount

Total Paid Amount

Total Loss (₵)

Collection Rate (%)

Total Active Customers

Time-Based Visuals

Monthly Billed vs. Paid amounts (combo chart)

Collection Rate trend over time

Segment Analysis

Loss comparison by Tariff Type: Residential, Commercial, Industrial

Loss comparison by Meter Type: Prepaid vs. Postpaid

Interactive Filters (Slicers)


Key Insights:

The simulated collection rate averages around 90.8%

Total simulated unpaid balances (losses) exceed ₵443,000

Postpaid meters contributed to all the unpaid balances

Some customers recorded 0 consumption despite having active meters, suggesting either possible power theft or faulty metering

How to Use This Project:

Open the powerbi_dashboard.pbix file using Power BI Desktop.

Use the slicers to explore different customer groups, months, and meter types.

Review the sql_queries.sql file to understand the logic and metrics used in building the dashboard.

The dataset is the excel file.



Author:
Louis Acheampong
📍 Accra, Ghana
🔌 Electrical Engineer with a strong focus on energy systems, data analytics, and utility performance optimization
📧 acheamponglouis5@gmail.com
