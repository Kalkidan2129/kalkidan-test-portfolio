
# Walmart Store Sales

## Project Summary

Developed an interactive Power BI dashboard that visualizes year‑over‑year sales for 45 Walmart stores across the United States from February 2010 to October 2012, highlighting trends during the post‑recession recovery period.

---

## Business Problem

Walmart’s regional stores needed a clear view of how the 2008‑09 recession impacted weekly sales and how factors such as holidays and unemployment rates influenced performance. Decision‑makers required a single source of truth to monitor sales health and identify under‑performing locations.

---

## Objective

- Import and cleanse the raw CSV sales data in Power BI Desktop.
- Build a robust data model with calendar, relationship, and conditional columns for holidays and unemployment.
- Create DAX measures and visualizations that enable YOY comparison and KPI tracking.

---

## Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M language)
- Excel (for initial CSV handling)
- Colaberry Power BI Cloud
- SQL‑style data modeling

---

## Project Workflow

- Import the Walmart sales CSV into Power BI Desktop and load the data.
- Create a Calendar table and a Refresh Date table using DAX and Power Query.
- Establish relationships between the sales table and the Calendar table.
- Add conditional columns for holiday flags and unemployment rate groups, then apply custom sort orders.
- Develop DAX measures (Total Sales, Sales per Month, Avg Sales, Sales YOY) and design the final dashboard with branding.

---

## Key Insights

- A dedicated Calendar table enables consistent time‑intelligence calculations such as year‑over‑year growth.
- Conditional columns for holiday weeks and unemployment groups reveal seasonal and economic drivers of sales variance.
- Custom sort columns ensure that month names and categorical flags display in logical order on visuals.
- DAX‑based YOY measure provides a quick snapshot of performance relative to the same period in the prior year.

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Empowers store managers to pinpoint periods of sales decline linked to economic factors.
- Facilitates data‑driven scheduling of promotions around identified holiday spikes.
- Supports strategic resource allocation by highlighting stores that recovered faster post‑recession.

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
