
# Walmart Store Sales

## Project Summary

Developed an interactive Power BI dashboard that visualizes year‑over‑year sales for 45 Walmart stores across the United States from February 2010 to October 2012. The solution integrates calendar tables, custom sorting, and DAX measures to enable drill‑down analysis of sales trends during the post‑recession period.

---

## Business Problem

Walmart’s regional stores needed a clear view of how the 2008‑09 recession impacted weekly sales and how factors such as holidays and unemployment rates influenced performance. Existing reports were static and did not allow easy comparison across time periods or stores.

---

## Objective

- Import and cleanse the raw CSV sales data in Power BI Desktop.
- Build a robust data model with date, holiday, and unemployment dimensions.
- Create visualizations and DAX measures that reveal YoY sales trends and key drivers.

---

## Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M language)
- Excel (for initial data review)
- CSV data source
- Power BI Cloud (deployment)
- Data modeling relationships

---

## Project Workflow

- Import the Walmart sales CSV into Power BI Desktop and load the data.
- Create a Calendar table and a Refresh Date table using DAX formulas.
- Establish relationships between the Calendar and Walmart tables.
- Add conditional columns for holiday flags and unemployment rate groups, then apply custom sort orders.
- Develop DAX measures (Total Sales, Sales per Month, Avg Sales, Sales YoY) and design the final dashboard with logos and titles.

---

## Key Insights

- A dedicated Calendar table enables consistent time‑intelligence calculations such as year‑over‑year growth.
- Conditional columns for holiday weeks and unemployment groups help isolate external factors affecting sales.
- Custom sort columns ensure that month names and categorical flags display in logical order on visuals.
- DAX measures provide quick access to total sales, average sales, and YoY percentage change for each store.

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Empowers store managers to identify periods of sales decline or growth quickly.
- Supports data‑driven decisions on inventory and promotional planning around holidays and economic conditions.
- Facilitates ongoing monitoring by publishing the dashboard to Power BI Cloud for stakeholder access.

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
