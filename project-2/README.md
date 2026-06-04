
# Walmart Store Sales

## Project Summary

Developed an interactive Power BI dashboard that visualizes year‑over‑year sales for 45 Walmart stores across the United States from February 2010 to October 2012. The solution integrates CSV data, custom date tables, conditional columns, and DAX measures to enable detailed sales trend analysis during the post‑recession period.

---

## Business Problem

Walmart’s regional stores needed a clear view of how the 2008‑09 recession impacted weekly sales and how factors such as holidays and unemployment rates influenced performance. Existing reports were static and did not allow drill‑down by time or store.

---

## Objective

- Import and cleanse the raw Walmart sales CSV in Power BI.
- Create a robust date model and related DAX calculations for YoY and average metrics.
- Design a polished, brand‑aligned dashboard that highlights key sales drivers.

---

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query (M)
- Excel (for initial data review)
- CSV data source
- Power BI Cloud (deployment)
- Custom visuals for logos and titles

---

## Project Workflow

- Import the Walmart sales CSV into Power BI Desktop.
- Build a Calendar table and a Refresh Date table using DAX and Power Query.
- Establish relationships between the sales table and the Calendar table.
- Create conditional columns for holiday flags and unemployment rate groups, then apply custom sort orders.
- Develop DAX measures (Total Sales, Sales per Month, Avg Sales, Sales YoY) and embed branding elements to finalize the dashboard.

---

## Key Insights

- A dedicated Calendar table enables accurate month‑level aggregation and YoY comparisons.
- Conditional columns for holiday weeks and unemployment groups reveal how external factors correlate with sales spikes or dips.
- Custom sort columns ensure that month names and categorical flags display in logical order rather than alphabetical.
- Embedding corporate logos and a clear title improves stakeholder adoption and reinforces brand identity.

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Provides store managers with a single source of truth for tracking sales recovery after the recession.
- Allows rapid identification of under‑performing periods linked to holidays or economic conditions, supporting targeted merchandising actions.
- Facilitates data‑driven decision‑making through an easily shareable Power BI Cloud dashboard.

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
