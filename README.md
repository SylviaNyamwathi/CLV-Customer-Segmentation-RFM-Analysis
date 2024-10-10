# RFM and CLV Analysis Project

## Overview
This project consists of two parts:
1. **RFM (Recency, Frequency, Monetary) Analysis:** Conducted on customer data from December 1, 2010, to December 1, 2011, to segment customers based on their purchasing behavior.
2. **Customer Lifetime Value (CLV) Analysis:** A follow-up task to estimate CLV using cohort analysis for more reliable results.

## Part 1: RFM Analysis
### Customer Segmentation
- Customers were segmented into groups based on their RFM scores:
  - **Top Customers**
  - **Loyal Customers**
  - **Can't Lose Them**
  - **Promising**
  - **Customers Needing Attention**
  - **About to Sleep**
  - **At Risk**
  - **Hibernating**

### Visualization
The RFM analysis results were visualized using **Power BI**, highlighting key customer segments to help the marketing team focus on areas that drive the most value.

### Key Insights
- **Top Customers**: Should be prioritized for retention strategies.
- **Loyal Customers**: Great candidates for loyalty programs and upselling.

## Part 2: Customer Lifetime Value (CLV) Analysis Using Cohorts
### Objectives
Your manager requested a more robust approach to calculating CLV, moving beyond Shopify’s simple formula to a cohort-based analysis. The focus is to understand how revenue from each cohort of users evolves over time.

### Adjustments
1. **Inclusion of All Users:** We expanded the analysis to include all website visitors, not just those who made a purchase.
2. **Cohort Analysis:** We examined the data using weekly cohorts to track how users engage over a period of 12 weeks.

### Analysis Steps
1. **Data Extraction:** Queried the `turing_data_analytics.raw_events` table to pull data on weekly revenue divided by registrations (first website visit as registration).
2. **Calculations:** Calculated Weekly Average Revenue, Cumulative Revenue, and Revenue Prediction by Cohorts.
3. **Visualization:** Applied conditional formatting to display trends in the cohort analysis.

## SQL Query and Data
You can find the SQL queries and detailed results for both the RFM and CLV analysis in the Excel file linked [here](https://1drv.ms/x/c/8a2481f5177c1dbe/EUo7s8bk4xRGseCeAUvLFaABck84ycuUBFfVL-S3rrqLyw?e=QewM83).

## Conclusion
This project highlights the importance of segmenting customers and accurately calculating CLV to focus on high-value customer groups and optimize marketing strategies. The use of cohort analysis provided a more actionable understanding of customer retention patterns and lifetime value.
