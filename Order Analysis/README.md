# Excel Dashboard for Order Analysis

## Executive Summary

This project focuses on developing an interactive Excel dashboard for analyzing sales order data. The dashboard provides insights into key metrics such as total sales, orders, and returns, helping stakeholders make informed business decisions. The project leverages Excel functions like VLOOKUP/XLOOKUP, PivotTables, and Slicers to integrate and visualize data dynamically.

## Project Summary

The Excel Dashboard for Order Analysis is designed to:

1. Summarize order insights, including total sales, total quantity ordered, total profit, and average discount.

2. Integrate returns data to assess the impact of product returns on overall sales and profit.

3. Use interactive slicers to filter data dynamically by region and manager.

4. Provide stakeholders with clear visualizations to support data-driven decision-making.

## Project Scope

1. Extracted KPIS for Total Sales, Total Quantity Ordered, Total Profit, Average Discount. Brokendown by: Product Category, Customer Segment, Region and Used PivotCharts to enhance data visualization.

2. Integrated Returns Data Using XLOOKUP/VLOOKUP to match and bring relevant information from the Returns Sheet into the dashboard. Highlighted orders that have been returned, using the Return Status field.

3. Created Slicers for Dynamic Filtering: Used XLOOKUP/VLOOKUP to pull Manager information from the Users table based on Region.

Implemented Slicers to filter the dashboard by: Region, Salesperson (Manager), and segments.

## Dataset Used

The dataset consists of:

1. Orders Sheet: Contains order details, including product category, region, sales, and profit.

2. Returns Sheet: Lists returned orders with their respective order IDs and return status.

3. Users Table: Maps regions to their respective sales managers.

## Methodology

### 1. Data Cleaning

Removed duplicates, corrected formatting issues, and standardized column names.

### 2. Data Processing & Modeling

Added calculated columns for return status, profit margins, and order priorities.

Used XLOOKUP/VLOOKUP to integrate returns data.

Created structured PivotTables for analysis.

### 3. Dashboard Development

Designed a fully interactive dashboard with:

1. Key metrics summary

2. PivotTables & PivotCharts

3. Slicers for real-time filtering

4. Key Performance Indicators (KPIs)

Total Sales – Revenue generated from orders.

Total Quantity Ordered – Number of units sold.

Total Profit – Net profit after expenses.

Average Discount – The average discount applied across orders.

Return Rate – Percentage of orders returned.

Sales Distribution by Category & Region – Identifies top-performing segments.

## Conclusions

Key Findings:

1. Certain product categories contributed more significantly to total sales and profit.

2. Some customer segments and regions drove higher revenue, while others have higher return rates.

3. Order priority impacted profit margins significantly, requiring an optimized sales strategy.

4. A few managers handled disproportionately profitable orders, suggesting a need for resource balancing.

## Recommendations:

1. Focus marketing efforts on high-performing product categories.

2. Investigate regions with high return rates to address potential quality or fulfillment issues.

3. Optimize order prioritization strategies to maximize profit margins.

4. Providedtargeted training for sales managers handling underperforming regions.
