# Arket Power BI Sales & Business Intelligence Dashboard

A multi-page **Microsoft Power BI** dashboard designed to analyze sales performance, products, customers, salespeople, and month-on-month business trends.

> **Portfolio project:** This repository contains the Power BI `.pbix` file and project documentation so recruiters can review the dashboard structure, analytical areas, and Power BI skills demonstrated.

## Dashboard Overview

The report contains **9 report pages**:

| Page | Purpose |
|---|---|
| **Home Page** | Navigation landing page for the report |
| **Sales Dashboard** | High-level sales and quantity performance, fiscal-year comparison, and area-wise sales |
| **Product Comparison by Year** | Compare product performance across fiscal years |
| **Product Group Wise Sales** | Analyze sales by product groups and sub-groups |
| **Customer Dashboard** | Explore customer-level and geographic sales information |
| **Sale person** | Analyze salesperson-level performance |
| **Month On Month** | Monitor monthly sales trends and comparisons |
| **Inter Group** | Analyze performance across groups/categories |
| **Visuals** | Additional/custom visual analysis used within the report |

## Key KPIs & Analysis Areas

The report includes measures/visuals for metrics such as:

- Total Sales Value (Cr)
- Total Sale Quantity
- Current Day Sales (Cr)
- Current Day Quantity (Lakh)
- Previous Day Sales (Cr)
- Previous Day Quantity (Lakh)
- Current Year Month Sales
- Last Year Month Sales
- Sales Variance
- Sales Variance %
- Average Sale Value
- Average Sale Quantity
- Average Value by Month
- Average Quantity by Month

## Dimensions & Filters

The report uses interactive filters/slicers covering business dimensions including:

- Fiscal Year
- Fiscal Quarter
- Month Name
- Country
- State
- City
- Area
- Customer / Company
- Salesperson
- Product / Item
- Main Group
- Item Group
- Sub Group
- Control Account

## Power BI Skills Demonstrated

- Power BI dashboard development
- Data modelling and business-oriented reporting
- DAX measures and calculated metrics
- KPI design and performance tracking
- Time-based analysis using fiscal year/month dimensions
- Interactive slicers and report navigation
- Drill/filter-based analysis
- Sales variance analysis
- Product, customer, geography and salesperson analysis
- Data visualization and dashboard UX
- Multi-page report design

## Report Structure

The report uses business-oriented entities such as `FactSales` and `Calendar` in its visual definitions. The sales model contains fields for quantity, value, customer, product, geography, salesperson, and time dimensions.

## Repository Contents

```text
Arket-PowerBI-Dashboard/
├── README.md
├── Arket_PowerBI_Dashboard.pbix
├── docs/
│   ├── project-details.md
│   └── model-overview.md
└── screenshots/
    └── README.md
```

## How to View the Project

1. Download `Arket_PowerBI_Dashboard.pbix` from this repository.
2. Open the file using **Microsoft Power BI Desktop**.
3. Navigate through the report pages using the built-in navigation.
4. Use the slicers and filters to explore the analysis.

## Portfolio Notes

The `.pbix` file is the primary project artifact. GitHub does not natively render an interactive Power BI report from a `.pbix` file, so screenshots are recommended for the repository preview.

For a public portfolio, avoid committing confidential company data, credentials, connection strings, or proprietary datasets. If the source data is not public, keep only the dashboard artifact and non-sensitive documentation, or replace sensitive data with a sanitized sample before publishing.

## Author

**Mansi Bhujade**  
Data Analyst | Power BI | SQL | Python | Excel

