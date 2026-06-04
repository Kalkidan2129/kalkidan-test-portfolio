
# Walmart Store Sales

## Project Summary

A comprehensive sales analysis dashboard evaluating year-over-year performance for 45 random Walmart stores across the US. The project analyzes sales trends between February 2010 and October 2012, specifically examining the recovery period following the 2008 recession.

---

## Business Problem

Walmart stores faced significant sales impacts during the post-recession era, affecting discount and department store performance. There was a need to assess year-over-year sales trends and the influence of external factors like unemployment rates and holiday periods.

---

## Objective

- Analyze year-over-year (YOY) sales growth and average weekly sales across 45 US stores.
- Evaluate the impact of holiday weeks and unemployment rates on store sales performance.
- Develop a dynamic Power BI dashboard to visualize sales metrics and consumer price index (CPI) trends.

---

## Tools & Technologies

- Power BI
- Power BI Desktop
- DAX
- Excel
- Power Query
- CSV

---

## Project Workflow

- Imported Walmart sales CSV data into Power BI Desktop for analysis.
- Developed a custom Calendar table using DAX and established relationships between data tables.
- Engineered conditional columns to categorize holiday flags and unemployment rate groups.
- Implemented custom sorting for holiday and unemployment columns to ensure accurate visual representation.
- Created complex DAX measures for Total Sales, Sales Per Month, Average Sales, and YOY Sales growth.

---

## Key Insights

- Year-over-year sales growth can be calculated by comparing current average sales against the previous year's performance using DATEADD.
- Sales performance varies based on holiday flags, requiring specific conditional categorization for analysis.
- Unemployment rates serve as a critical external variable impacting store sales trends.
- The use of a dedicated Calendar table allows for precise time-intelligence analysis across months and years.

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Enabled data-driven assessment of sales recovery trends following the 2008 recession.
- Provided visibility into how holiday periods specifically influence weekly sales volume.
- Established a scalable reporting framework to monitor the correlation between unemployment rates and retail performance.

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
