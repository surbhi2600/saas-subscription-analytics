# SaaS Subscription Analytics

An end-to-end data analytics project exploring SaaS subscriptions, invoice status, billing trends, and product usage using Python, PostgreSQL, and Power BI.

## Project Overview

The goal of this project is to analyze subscription and billing data and turn it into useful business insights through SQL analysis, exploratory data analysis (EDA), and an interactive Power BI dashboard.

**Note:** This project uses synthetic data for educational and portfolio purposes. The findings do not represent a real company's performance.

## Tools & Technologies

- **Python** — data exploration and analysis
- **Pandas** — data manipulation
- **Jupyter Notebook** — exploratory data analysis
- **PostgreSQL** — relational data storage and querying
- **SQL** — aggregations and business analysis
- **Power BI** — interactive dashboard and visualizations

## Dataset Overview

The project contains six related tables:

| Table | Description |
|---|---|
| organizations | Organization records |
| users | User information |
| plans | Subscription plan details |
| subscriptions | Subscription records |
| invoices | Billing and invoice records |
| usage_events | Product activity events |

The tables contain approximately **259,208 records** in total.

## Project Workflow

1. Explored the dataset structure and table columns.
2. Loaded the data into PostgreSQL.
3. Checked table sizes, data types, and data quality.
4. Performed exploratory data analysis using Python and Pandas.
5. Analyzed invoice statuses, billing trends, subscription plans, and product usage.
6. Connected PostgreSQL tables to Power BI.
7. Created KPI cards, charts, and an interactive plan slicer.

## Dashboard KPIs

- Total Organizations: **3,000**
- Total Subscriptions: **4,200**
- Total Invoices: **46,000**
- Paid Invoices: **40,486**

## Dashboard Visualizations

- Monthly Paid Invoice Amount
- Invoice Status Distribution
- Product Usage by Event Type
- Subscriptions by Plan
- Interactive Plan Name Slicer

## Key Findings

- The dataset contains 40,486 paid invoices, 3,210 failed invoices, 1,360 refunded invoices, and 944 open invoices.
- `report_run` is the most frequent event type in the product usage data.
- Enterprise has the highest subscription count among the listed plans.
- Monthly paid invoice amounts vary over time and can be explored in the Power BI report.

Invoice amounts are not treated as final net revenue because refund accounting and revenue recognition rules have not been established.

## Project Files

- `01_invoices_eda.ipynb` — notebook for exploratory data analysis.
- `SaaS_Subscription_Analytics_Dashboard.pbix` — Power BI dashboard file.

A local PostgreSQL setup may be required to reproduce the database analysis.



