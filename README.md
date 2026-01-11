\# Regulatory Compliance Dashboard (AML Transaction Monitoring)



\## Overview

This project builds an end-to-end compliance analytics solution using realistic financial transaction data.

It includes a dimensional data model, rules-based alert logic, and a Power BI dashboard for monitoring

suspicious activity and supporting investigations.



\## Key Questions Answered

\- What % of transactions are flagged as suspicious and how is it trending over time?

\- Which entities/accounts drive the most alerts and why?

\- What alert typologies dominate (velocity, structuring, concentration, large-value)?

\- What transactions should investigators review first?



\## Deliverables

\- Power BI dashboard (.pbix)

\- Curated analytics tables (generated locally)

\- Alert rules and KPI definitions

\- Documentation (data dictionary + walkthrough)



\## Repo Structure

\- `/data/raw` (local only) downloaded dataset (ignored by git)

\- `/data/interim` (local only) cleaned outputs

\- `/data/processed` (local only) curated tables for BI

\- `/notebooks` analysis + feature engineering

\- `/sql` schema + KPI/alert logic

\- `/dashboards` Power BI file

\- `/docs` documentation + screenshots



\## How to Reproduce

1\. Download the dataset (see `data/raw/README.md`)

2\. Run notebooks in order:

&nbsp;  - `01\_eda.ipynb`

&nbsp;  - `02\_feature\_engineering.ipynb`

&nbsp;  - `03\_alert\_rules.ipynb`

3\. Open the Power BI file in `/dashboards` and refresh.



\## Tools

Python, SQL, Power BI



