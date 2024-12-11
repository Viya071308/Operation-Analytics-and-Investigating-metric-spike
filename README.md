# Operation Analytics and Metric Spike Investigation

## Project Description

This project focuses on **Operation Analytics**, an essential process to evaluate a company's operations and identify areas for improvement. By analyzing data from various teams such as operations, support, and marketing, valuable insights are derived to enhance workflows, automation, and team collaboration. 

The primary goal of this project is to investigate daily metric fluctuations, such as:
- Declines in daily engagement
- Drops in sales

Understanding these metrics helps businesses make informed decisions, improve productivity, and optimize overall performance.

## Technologies Used
- **SQL Workbench**: Version 8.0 CE
- **Data Sources**: Company-provided datasets

## Project Approach

1. Familiarization with data and clarification of key components like `job_id`, `actor_id`, and `event`.
2. Loading datasets into SQL Workbench for analysis.
3. Investigating specific metrics to answer critical business questions, such as:
   - Why daily engagement decreased.
   - Causes of sales drops.
4. Performing daily and long-term metric spike investigations.

## Case Studies

### **Case Study 1: Job Data Analysis**
- Calculated the number of jobs reviewed per hour in November 2020.
- Computed 7-day rolling averages for throughput and compared with daily metrics.
- Determined percentage shares of languages in job data.
- Identified and displayed duplicate rows in the dataset.

#### Key Insights:
1. The **7-day rolling average** provides a better overview compared to daily metrics.
2. The **Persian language** accounted for the largest share of jobs (37.5%).
3. Found **two duplicate rows** when data was partitioned by `job_id`.

---

### **Case Study 2: Investigating Metric Spikes**
1. Weekly user engagement trends.
2. User growth for the product.
3. Weekly retention rates for sign-up cohorts.
4. Weekly engagement per device type.
5. Email engagement metrics (email open and click rates).

#### Key Insights:
1. Weekly user engagement peaked in **weeks 18–31**, with a decline afterward.
2. A total of **9,381 active users** were identified between week 1 of 2013 and week 35 of 2014.
3. Most engagement occurred on **MacBooks and iPhones**.
4. Email open rate: **34%**, click rate: **15%**.

---

## Queries and Techniques

A variety of SQL queries were employed to derive insights, including:
- Calculations of rolling averages and percentages.
- Identifying duplicate rows.
- Weekly and cohort-based analyses.
- Device-specific user engagement tracking.
- Email engagement metrics computation.

## Results

The analyses provided actionable insights for addressing operational inefficiencies and improving user engagement, sales, and product quality.
