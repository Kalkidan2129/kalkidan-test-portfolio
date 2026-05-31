
# Walmart Store Sales

## Project Summary

This project builds an interactive Power BI dashboard to assess year-over-year sales across 45 US Walmart stores from February 2010 through October 2012. It contextualizes weekly sales performance during the post-recession recovery period following the 2008 economic downturn. The solution combines time intelligence, conditional categorization, and custom DAX measures, deploying the final report to Power BI Cloud.

---

## Business Problem

Discount and department stores faced significant sales impacts while emerging from the great recession of 2008, creating a need for clearer operational visibility. Walmart required a systematic way to evaluate year-over-year sales fluctuations across 45 randomly selected US stores during the 2010–2012 recovery window. This project tackles that need by analyzing weekly sales data alongside external economic and seasonal variables to understand performance drivers.

---

## Objective

- Assess year-over-year sales performance across 45 Walmart stores from Feb 2010 to Oct 2012
- Build time intelligence and conditional categorizations (holidays, unemployment) to contextualize sales trends
- Develop and deploy an interactive Power BI dashboard for retail analytics and reporting

---

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Colaberry Power BI Cloud
- Excel
- CSV / Text Data Sources

---

## Project Workflow

- Import the Walmart sales CSV dataset into Power BI Desktop using the Text/CSV connector
- Create a Calendar table with DAX and a Refresh Date table in Power Query to enable time-series tracking
- Model relationships between the sales and calendar tables, then engineer conditional columns for holiday flags and unemployment groups
- Develop custom sorting rules and DAX measures for total sales, average sales, sales per month, and year-over-year comparisons
- Finalize the dashboard with branded logos, titles, and publish the report to Power BI Cloud

---

## Key Insights

- Year-over-year DAX measures enable direct comparison of average weekly sales across the 2010–2012 post-recession timeline
- Holiday conditional columns distinguish weekly sales periods flagged as holiday versus non-holiday weeks
- Unemployment conditional columns categorize stores by regional economic conditions to contextualize sales figures
- Calendar table integration supports monthly seasonality analysis and consistent period-over-period reporting

---

## Final Dashboard / Project Preview

![Final Dashboard](./screenshots/preview.png)

---

## Business Impact

- Delivers a unified Power BI dashboard for assessing year-over-year sales performance across 45 US Walmart stores
- Embeds holiday and unemployment contextual data directly into the analytical workflow to support root-cause exploration
- Publishes interactive reporting to the cloud, making retail performance insights accessible for stakeholder review

---

## Portfolio Navigation

[← Back to Portfolio Home](../README.md)
