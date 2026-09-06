# Sales data analysis in Excel

A complete Excel-based analysis of a global sales transaction dataset, built to uncover revenue and profit trends across regions, product categories, sales channels, and order types — and presented through an interactive PivotTable-driven dashboard.

---

## Project Overview

This project analyzes 5,000 sales transactions recorded between 2015 and 2022, spanning 185 countries across 7 world regions. Using Excel PivotTables, PivotCharts, and Slicers, the raw data is transformed into a set of clear, interactive summaries that reveal how revenue and profit are distributed across the business — by time period, product category, geography, sales channel, and order priority.

The end result is a single-view dashboard that lets a viewer filter and explore the data without needing to touch the underlying transactions.

## Problem Statement

Raw transactional sales data is hard to act on in its native form — thousands of individual rows don't tell a decision-maker where the business is winning or losing. This project set out to answer: **which regions, product categories, and sales channels are actually driving revenue and profit, and where is performance falling short?**

## Objectives

- Consolidate and organize raw sales records into an analyzable structure
- Break down total revenue by month, item type, region, and order priority
- Identify the most and least profitable item types, regions, and sales channels
- Quantify cancelled orders and compare Online vs. Offline channel performance
- Build an interactive, visual dashboard for at-a-glance reporting

## Dataset / Data Source

- **Source file:** [`sales_data_original.xlsx`](https://github.com/David-Onwudiwe/excel_sale_data_analysis/blob/main/sales_data_original.xlsx)
- **Size:** 5,000 records
- **Fields:** Region, Country, Item Type, Sales Channel, Order Priority, Order Date, Order ID, Ship Date, Units Sold, Unit Price, Unit Cost, Total Revenue, Total Cost, Total Profit
- **Date range:** January 2015 – December 2022

## Tools & Technologies

- **Microsoft Excel** — PivotTables, PivotCharts, Slicers, formulas, and dashboard design

## Project Workflow / Methodology

1. **Data Collection** — Imported the raw transactional dataset into a working sheet.
2. **Data Preparation** — Structured the data as an Excel Table to support dynamic PivotTable references.
3. **Analysis** — Built four PivotTables summarizing Total Revenue by Month, Item Type, Region, and Order Priority. A dedicated Calculations sheet computes profit per item type, profit per region, cancelled order counts, and sales channel counts.
4. **Visualization** — Created PivotCharts (line, 3D bar, and 3D pie charts) from the pivot tables.
5. **Dashboard Assembly** — Combined charts and slicers onto a single Dashboard sheet for interactive, filterable reporting.

### Data Cleaning / Preparation

The preparation process included:

- Clearing all previous filters from the dataset
- Reviewing the structure and fields in the dataset
- Reviewing date, text, and numerical fields
- Checking transaction-level revenue, cost, and profit values
- Preparing the dataset for PivotTable analysis
- Creating supporting worksheets for summarized analysis

### Analysis

- **Revenue by Month** — Total revenue aggregated across all years, by calendar month
- **Revenue by Item Type** — Total revenue across 12 product categories (Baby Food, Beverages, Cereal, Clothes, Cosmetics, Fruits, Household, Meat, Office Supplies, Personal Care, Snacks, Vegetables)
- **Revenue by Region** — Total revenue across 7 global regions
- **Revenue by Order Priority** — Total revenue by order priority level (Cancelled, Low, Medium, High)
- **Key Metrics (Calculations sheet)** — Profit per item type, profit per region, cancelled order count, and Online vs. Offline order counts

## Visualizations

The Dashboard sheet brings together 8 PivotCharts (in two style variants) and 2 slicers for interactive filtering:

| Chart | Type | What It Shows |
|---|---|---|
| Total Revenue by Month | 3D Line Chart | Revenue trend across the calendar year |
| Total Revenue by Item Type | 3D Clustered Bar Chart | Revenue comparison across the 12 product categories |
| Total Revenue by Region | 3D Clustered Column Chart | Revenue comparison across the 7 global regions |
| Total Revenue by Order Priority | 3D Pie Chart | Revenue share by order priority level, with data labels |

Slicers let a viewer filter the entire dashboard interactively, so all charts update together.

**Dashboard Preview:**

![Sales Dashboard](https://github.com/David-Onwudiwe/excel_sale_data_analysis/blob/main/sales_dashboard_screenshot.png)

## Key Findings / Insights

- **Total revenue across all transactions: ~$6.63 billion**
- **Most profitable item type:** Cosmetics (~$372.4M total profit), followed by Household and Office Supplies
- **Least profitable item type:** Fruits (~$5.6M total profit)
- **Most profitable region:** Sub-Saharan Africa (~$531.1M profit), followed by Europe
- **Least profitable region:** North America (~$41.2M profit)
- **Sales channel split is nearly even:** 2,504 Offline orders vs. 2,496 Online orders — Offline is marginally more profitable
- **1,174 orders** were flagged as "Cancelled" priority
- By revenue, **Sub-Saharan Africa** ($1.81B) and **Europe** ($1.70B) lead all regions; **North America** ($151M) trails far behind
- By revenue, **Household** ($1.40B) and **Office Supplies** ($1.37B) are the top-generating categories, while **Fruits** ($21.8M) is lowest
- Monthly revenue is fairly stable, peaking in **May** (~$617.6M) and dipping lowest in **September** (~$486.7M)
- **"Medium" priority orders** generated the most revenue (~$1.78B), closely followed by "High" priority (~$1.71B)

## Recommendations

- Prioritize **Cosmetics, Household, and Office Supplies** — the strongest profit and revenue drivers — for continued marketing and inventory focus
- Investigate the underperformance of **Fruits** and **North America** to understand whether pricing, cost structure, demand, or logistics are limiting factors
- Consider expanding distribution or marketing investment in **Sub-Saharan Africa and Europe**, the top-performing regions
- Review the **1,174 cancelled orders** to identify root causes (stock issues, fulfillment delays, pricing disputes) and reduce lost revenue
- Test channel-specific promotions for both Online and Offline, since performance between the two is closely matched

## Project Structure

```
excel_sale_data_analysis/
│
├── sales_data_original.xlsx     # Raw source dataset
├── Sales data analysis in Excel.xlsx   # Full workbook with PivotTables, calculations, and dashboard
└── README.md                    # Project documentation
```

[Add or adjust file/folder descriptions if the repository structure differs]

## How to Run / Use the Project

1. Download or clone the repository.
2. Open **`Sales data analysis in Excel.xlsx`** in Microsoft Excel (Excel 2016 or later recommended for full PivotChart and Slicer support).
3. Navigate to the **Dashboard** sheet to view the interactive summary.
4. Use the slicers to filter the dashboard by region, order priority, or other available fields.
5. Explore the underlying **Sales Data**, pivot summary sheets, and **Calculations** sheet for the full breakdown behind each chart.

## Results / Conclusion

This project shows how a large, unstructured sales dataset can be turned into a clear, decision-ready reporting tool using only native Excel features — PivotTables, PivotCharts, and Slicers. The analysis highlights where the business generates the most value (Cosmetics, Household, Office Supplies, and the Sub-Saharan Africa and Europe regions) and flags areas that may need further investigation (Fruits, North America, and cancelled orders), demonstrating an end-to-end workflow from raw data to actionable insight.

## Author / Contact

**David Onwudiwe**
- LinkedIn: [linkedin.com/in/david-onwudiwe-092271191](https://linkedin.com/in/david-onwudiwe-092271191)
- GitHub: [github.com/David-Onwudiwe](https://github.com/David-Onwudiwe)
- Project Link: [Sales data analysis in Excel.xlsx](https://github.com/David-Onwudiwe/excel_sale_data_analysis/blob/main/Sales%20data%20analysis%20in%20Excel.xlsx)
