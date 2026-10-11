# Sales Report Dashboard — Power BI

An interactive sales analytics dashboard built in **Microsoft Power BI** to explore sales pipeline performance, revenue trends, sales-team results, and account/product insights.

## Overview

The report brings key sales metrics into one place so users can review overall performance, compare sales representatives and regions, and investigate which sectors, accounts, and products contribute to revenue.

## Dashboard Pages

### 1. Executive Overview
- Total Revenue
- Overall Win Rate
- Total Pipeline Opportunities
- Average Cycle Time (Days)
- Revenue by sector and deal stage
- Revenue by office location
- Monthly revenue trend

### 2. Sales Team Performance
- Revenue and won revenue by sales representative
- Win rate and days to close
- Opportunities handled by sales agent
- Comparisons by manager and regional office

### 3. Account & Product Deep-Dive
- Revenue by sector and product
- Account-level revenue and total spend
- Primary product analysis
- Sales price and average-value comparisons
- Account attributes such as employee tier and active-account status

## Tools & Technologies

- **Microsoft Power BI Desktop** — report development and interactive visualizations
- **DAX** — measures and calculations used in the report
- **Power BI data model** — sales pipeline, product, account, sector, and sales-team fields

## File Included

- `Sales Report.pbix` — the Power BI report file. Open it using Power BI Desktop to explore the report and its visuals.

## How to Use

1. Download or clone this repository.
2. Open `Sales Report.pbix` in Microsoft Power BI Desktop.
3. If Power BI prompts for data-source credentials or paths, configure them for your environment.
4. Refresh the data if the connected source is available and refresh is required.
5. Use the report pages and visual interactions (such as filters and selections) to explore performance by time, sector, office, account, product, manager, and sales agent.

## Key Questions This Dashboard Helps Answer

- How much revenue has been generated?
- What is the overall win rate and average sales-cycle duration?
- How does revenue change month by month?
- Which sectors, products, and office locations contribute most to revenue?
- How do sales agents and managers compare on revenue, win rate, and opportunities?
- Which accounts and products warrant a closer look?

## Notes

- Metric values depend on the data loaded into the report and may change when the dataset is refreshed.
- The `.pbix` file contains the report and its Power BI model. External data-source access, credentials, or refresh configuration may still be required in another environment.
- Review the report and data permissions before publishing or sharing the file publicly.

## Author

Created as a Power BI sales analytics project.
