# Customer Churn Analysis Dashboard

Multi-page **Power BI** dashboard analyzing telecom customer churn — from raw data through to a data-driven retention strategy.

> **Dataset:** IBM Telco Customer Churn (public dataset, 7,043 customers, 21 features)

---

## Executive Overview

![Executive Overview](Executive%20Overview.jpeg)

KPIs at a glance: **7K total customers**, **2K churned**, **26.54% churn rate**. Distribution of churn by monthly charges and contract type — identifying month-to-month contracts as the dominant risk segment.

---

## Churn Drivers

![Churn Drivers](Churn%20Drivers.jpeg)

A 4-quadrant breakdown of churn drivers across:
- **Internet Service** — fiber optic users show the highest churn count
- **Contract Type** — month-to-month is the biggest churn driver
- **Payment Method** — electronic check users churn more than other methods
- **Tenure** — low-tenure customers leave early

---

## Customer Profile

![Customer Profile](Customer%20Profile.jpeg)

Demographic deep-dive: customers by gender, dependents, and senior status. Findings: churn is similar across genders, but **customers without dependents churn more**. Avg monthly charge: $64.76. Avg tenure: 32 months.

---

## Action Plan

![Action Plan](Action%20Plan.jpeg)

Translates the analysis into a concrete retention strategy:
- Convert **month-to-month → yearly** contracts with discounts
- Target **new customers** with onboarding campaigns
- Push **automatic payments** (credit card / bank)
- Focus retention on **high-risk segments**

---

## Tech Stack

- **Power BI Desktop** — multi-page report design with cross-page filtering
- **DAX** — measures for churn rate, customer count, retention rate
- **Data modeling** — star schema with dimension tables
- **Drill-through filters** — for deeper customer-level analysis

## What's Inside

- **4 dashboard pages** — Executive Overview, Churn Drivers, Customer Profile, Action Plan
- **DAX measures** — Churn Rate %, Customer Count, Retention Rate, and supporting calcs
- **Visual storytelling layout** — KPIs, slicers, and drill-through navigation

## Files in This Repository

| File | Description |
|------|-------------|
| `Elie_Zeraoui_Telecom_Churn_Dashboard.pbix` | Power BI report file (open with Power BI Desktop) |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Source dataset (IBM Telco Customer Churn) |
| `Executive Overview.jpeg` | Page 1 preview |
| `Churn Drivers.jpeg` | Page 2 preview |
| `Customer Profile.jpeg` | Page 3 preview |
| `Action Plan.jpeg` | Page 4 preview |

## See It on LinkedIn

[View the project post on LinkedIn](https://linkedin.com/posts/elie-zeraoui-7a5a04267_dataanalytics-powerbi-businessanalysis-activity-7455634053501816833-W_we)

---

Built by **[Elie Zeraoui](https://github.com/elie-zeraoui)** — Data Analyst | Computer Science Graduate
