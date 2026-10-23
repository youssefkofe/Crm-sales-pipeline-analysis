# CRM Sales Pipeline Analysis

## Overview

This project uses Microsoft Power BI to analyze CRM sales opportunities, sales agent performance, product performance, and revenue trends.

The interactive dashboard helps explore sales pipeline distribution, win/loss outcomes, revenue contribution, and differences in sales performance.

## Business Questions

1. **Sales Pipeline Overview:** How are opportunities distributed across deal stages?
2. **Win/Loss Analysis:** What percentage of closed opportunities are won versus lost?
3. **Sales Agent Performance:** How does performance vary across sales agents?
4. **Product Performance:** Which products generate the highest revenue and have the best sales outcomes?
5. **Sales Trends Over Time:** How do closed opportunities and revenue change over time?

## Dashboard Preview

### 1. Sales Overview

![Sales Overview](Sales%20Overview.png)

### 2. Sales Agent Performance

![Sales Agent Performance](Sales%20Agent%20Performance.png)

### 3. Product Performance

![Product Performance](Product%20Performance.png)

## Key Findings

- **8,800** total sales opportunities.
- **6,711** closed opportunities: 4,238 won and 2,473 lost.
- **63.15%** overall win rate among closed opportunities.
- **10,005,534** in total recorded revenue.
- Darcy Schlecht recorded the highest revenue among sales agents, at approximately **1,153,214**.
- GTXPro generated the highest revenue among products, at approximately **3,510,578**.
- GTX Basic had the highest number of won opportunities among products, with **915**.

These findings describe observed patterns in the dataset and do not establish the causes of differences in sales performance.

## Data Preparation and Validation

Data preparation and quality checks were performed using Power Query and Power BI.

- Reviewed column data types and missing values.
- Examined deal-stage distributions and revenue values.
- Preserved blank close dates and close values for open opportunities.
- Retained opportunities with missing account names rather than inventing values or deleting records.
- Validated key totals for opportunities, closed opportunities, won opportunities, and revenue by product.
- Manually checked a product win-rate calculation against the Power BI measure.

## Tools and Skills

- Microsoft Power BI
- Power Query
- DAX measures
- Data modeling and relationships
- Data quality assessment and validation
- KPI design and interactive dashboards
- Business analysis and insight communication

## Dataset

**Source:** [Maven Analytics Data Playground — CRM Sales Opportunities](https://mavenanalytics.io/data-playground/crm-sales-opportunities)

The dataset includes sales pipeline opportunities, account information, product details, and sales team information.

## Project File

- `CRM-Sales-Pipeline-Analysis.pbix` — Interactive Power BI report.

## How to Explore the Project

1. Download the `.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. Navigate through the three dashboard pages.
4. Explore the visualizations and compare the metrics.

## Limitations

Some account names are missing from the source dataset. These records were retained, and the missing values remain a limitation of the analysis. Findings are descriptive and are limited to the fields available in the dataset.
