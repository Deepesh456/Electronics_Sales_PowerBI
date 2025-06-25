# Electronics Sales Dashboard – Power BI Project

This repository contains a Power BI dashboard that analyzes sales performance for an electronics company. Built using a multi-table relational dataset, the dashboard highlights revenue, profit, and customer trends using interactive visuals, slicers, and DAX measures.

## Files Included

- Electronics_Sales.pdf – Dashboard screenshot
- POWER_BI_UPDATED_PRODUCTS.xlsx – Updated dataset with electronics product names
- README.md – Project overview and documentation
- Electronics_Sales.pbix – Power BI file (optional, if permitted)

## Dashboard Features

- Slicers for dynamic filtering by:
  - Product
  - Customer
  - Channel
  - Date range
- KPI cards displaying:
  - Total Revenue
  - Total Profit
- Gauge chart to visualize current profit against a target
- Bar charts for:
  - Revenue by Product
  - Top Customers by Revenue
- Map visual showing Revenue by City
- Clean, modern layout with black background and white card visuals

## DAX Usage

Custom columns and measures were created using DAX to enable advanced analysis:

1. **Profit**  
   `Profit = [Total Revenue] - [Total Unit Cost]`

2. **Profit Margin (%)**  
   `Profit Margin (%) = DIVIDE([Profit], [Total Revenue], 0)`

These calculated fields were used in KPI cards, gauge charts, and data visuals to provide meaningful insights on business performance.

## Key Visuals

| Visual Type       | Description                        |
|-------------------|------------------------------------|
| Gauge Chart        | Displays profit vs. target         |
| Bar Charts         | Revenue by Product and Customer    |
| Map                | Revenue by City                    |
| Date Range Filter  | Select custom time period          |
| Dropdown Slicers   | Filter dashboard by key dimensions |

## Business Insights

- VoltAir Earbuds had the highest revenue contribution (₹25M+)
- Major customer segments include Medline and Pure Group
- Sales peaked between 2018 and 2019
- City-level data shows strong performance in key urban areas

## Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions) for calculated columns and KPIs
- Excel for structured input data

## Dataset Overview

The dataset consists of multiple related tables:
- Sales Orders
- Products
- Customers
- Regions

It includes fields such as Order Date, Revenue, Unit Cost, Product Index, Customer Index, and Region Index.
