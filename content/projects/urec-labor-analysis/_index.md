+++
title = "Understanding scheduled and actual labor"
summary = "Joining recreation scheduling and timeclock records to understand labor variance, with attention to matching quality and operational context."
description = "A UREC operations case study using SQL, Python, and Power BI to compare scheduled and actual work hours."
date = "2025-06-01"
weight = 1
category = "Operations analytics"
period = "2024–2025"
featured = true
layout = "detail"
tags = ["SQL", "Power BI", "Operations"]
showtoc = false
hideMeta = true
url = "/projects/urec-labor-analysis/"

[cover]
image = "/images/urec_dashboard.png"
alt = "Historical Power BI dashboard for scheduled and actual labor hours"
relative = false
hidden = true
+++

**Appalachian State University Recreation · 2024–2025**

## The operational question

How closely did actual work hours align with scheduled hours, and what could the differences tell us about scheduling and operations?

University Recreation used WhenToWork for scheduling and TimeClock Plus for timeclock records. The systems did not share a consistent employee identifier, making comparison difficult. My experience in recreation operations provided context for investigating those differences.

## My contribution

I used SQL and Python to prepare and combine the records, calculate differences between scheduled and actual hours, and examine patterns over time. The work produced a written report and a Power BI dashboard.

The analysis included name and date matching, treatment of missing or invalid records, and views of positive and negative hour differences. SQL handled preparation and aggregation; Python supported further analysis and visualization.

## What the report showed

The historical report describes **2,583 analyzed records** and a **net difference of 111.4 fewer actual hours than scheduled** across the 2024–2025 academic year.

That is a comparison with scheduled time. It does not establish savings caused by this analysis or show that an individual employee's time difference was inappropriate. Event cancellations, shift changes, and other operational conditions can affect the result.

## What matters when interpreting it

- **Matching quality:** name-based joins can introduce mismatches or omit records.
- **Record definitions:** employee-day duration differences and individual clock-out timing need distinct definitions.
- **Operational context:** the analysis lacked linked cancellation logs and complete role or facility detail.
- **Reconciliation:** the report's early-record count differs from its appendix, so that count needs verification against the original data.

The project demonstrates how joining disconnected operational sources can make a question inspectable. A next iteration would strengthen identifiers, reconcile the measures, and add context before recommending scheduling changes.

## Explore the work

- [Read the original report (PDF)](/documents/urec_labor_discrepancy.pdf)
- [Download the Power BI dashboard (PBIX)](/documents/Timeclock_Discrepancy_Analysis_Dashboard.pbix)

The original artifacts preserve the historical analysis. Their calculations have not been rerun as part of this portfolio update.
