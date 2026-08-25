# Global-Retail-Sales-Dashboard
Power BI dashboard analyzing global retail sales, profit, and returns across markets, regions, and product categories using DAX measures and interactive visuals.

An interactive Power BI dashboard analyzing global retail sales performance — 
covering revenue, profit, order volume, and product returns across multiple 
markets, regions, and product categories.

## Overview

This project turns raw retail order and returns data into a multi-page Power BI 
report, enabling stakeholders to track sales performance, profitability, and 
return trends at a glance — sliceable by market, region, category, and time period.

## Dashboard Pages

| Page | Focus |
|---|---|
| **Executive Overview** | High-level KPIs — Total Sales, Total Profit, Total Orders, Profit Margin |
| **Product Details** | Performance by Category and Product Name |
| **Region Details** | Sales and profit breakdown by Region and Market |
| **Returns Details** | Return Rate and Returned Orders analysis |

## Data Model

- **Orders** — Category, Market, Region, Segment, Product Name, Total Sales, 
  Total Profit, Total Quantity, Total Orders, Profit Margin
- **Returns** — Market, Returned Orders, Return Rate
- **Date** — Year, Year-Month (time intelligence for trend analysis)

## Key Metrics

- Total Sales, Total Profit, Profit Margin %
- Total Orders, Total Quantity
- Return Rate, Returned Orders
- Performance by Market, Region, Category, and Segment

## Tools Used

- Power BI Desktop
- Data Modeling (relationships between Orders, Returns, and Date tables)
- DAX measures (Total Sales, Total Profit, Profit Margin, Return Rate)
- Interactive slicers and cross-filtering across report pages

## Files

| File | Description |
|---|---|
| `Global_retail_sales_project.pbix` | Power BI report file — data model, DAX measures, and dashboard visuals |

## Key Insights

- [Add: which market/region had the highest sales and profit]
- [Add: which product category had the strongest margin]
- [Add: overall return rate and any category with disproportionately high returns]

## Author

Tanuja Mane
