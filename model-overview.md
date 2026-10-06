# Model & Field Overview

The Power BI report definition references a sales fact entity named `FactSales` and a calendar/time entity named `Calendar`.

## FactSales — observed business fields

- BILL_DATE
- QUANTITY
- VALUE
- COUNTRY
- STATE
- CITY
- AREA / Area Name
- CUSTOMER
- COMPANY
- SALESMAN
- ITEM
- ITEM_GROUP
- MAIN_GROUP
- SUB_GROUP
- CONTROL_ACCOUNT

## Calendar — observed time fields

- Fiscal Year
- Fiscal Quarter
- Month Name
- FINANCIAL_YEAR.1

## Measures / calculated metrics observed in report visuals

- Total Sales Value (Cr)
- Total Sale Quantity
- Current Day Sale (Cr)
- Current Day Qty (Lakh)
- Previous Day Sale (Cr)
- Previous Day Qty (Lakh)
- Current Year Month Sale
- Last Year Month Sale
- Sales Variance
- Sales Variance in %
- Avg Sale Quantity
- Avg Sale Value
- Avg Quantity by Month
- Avg Value by Month

> This document intentionally describes the report definition rather than exposing the underlying business data.
