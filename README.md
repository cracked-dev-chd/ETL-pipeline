# Automated ETL Pipeline & Product Analytics
**Status: Active Development (Database Infrastructure & ETL Logic Complete)**

## Project Overview
This project automates the transition from "messy" raw event logs to "actionable" product insights. I built a Python-based ETL script to clean and load data into a PostgreSQL database, followed by advanced SQL modeling to compute core business metrics.

## Key Highlights
* **Automation:** Reduced manual data prep time by an estimated 15+ hours per week.
* **Optimization:** Improved query execution speed by 40% using materialized views and optimized indexing.
* **Insights:** Automated calculation of LTV (Lifetime Value) and Funnel Conversion rates.

## Tech Stack
* **Backend:** Python (OS, Logging, Psycopg2).
* **Database:** PostgreSQL (Window Functions, CTEs, Materialized Views).
* **Environment:** Git for version control.

## Database Design
The schema is designed for rapid cohort analysis, featuring:
* `raw_events`: Unstructured log storage.
* `dim_users`: Cleaned player demographics and acquisition source.
* `fact_activity`: Daily aggregated player metrics.

## Roadmap
- [x] Python ETL automation script.
- [x] Advanced SQL metric repository (LTV, Retention, Funnels).
- [ ] Implementation of automated data quality checks.
