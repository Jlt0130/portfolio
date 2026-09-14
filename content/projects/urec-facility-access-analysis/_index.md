+++
title = "Understanding recreation facility use"
summary = "Exploring annual recreation access patterns and the data-quality checks needed before acting on demographic comparisons."
date = "2025-06-20"
weight = 3
category = "Operations analytics"
period = "2024–2025"
layout = "detail"
tags = ["Python", "Data visualization", "Data quality"]
showtoc = false
hideMeta = true
url = "/projects/urec-facility-access/"

[cover]
image = "/images/facility_heatmap.png"
alt = "Historical recreation facility access visualization"
relative = false
hidden = true
+++

**Appalachian State University Recreation · 2024–2025**

## The question

How did facility access vary by time of day, facility, and participant group, and what could those patterns contribute to operational planning?

## My contribution

I analyzed aggregated annual access counts in Python and created visualizations of hourly traffic and participant-group patterns. The resulting report connects those patterns to questions about staffing, programming, and access.

## What the analysis can support

The report identifies late-afternoon demand and differences among facilities. These are useful starting points for further investigation. Access records count visits, so they cannot establish the number of unique people participating or the duration of their visits.

## A data-quality finding to resolve

The original report flags a suspicious demographic pattern. In its Figure 5, the count labeled "Faculty, Staff, and Family" equals the sum of the student categories at every facility. This could reflect a subtotal being treated as a category; the original data and transformation steps are needed to determine the cause.

Demographic percentages and related recommendations therefore need revalidation. A future analysis would also need facility hours, capacity, and compatible population definitions before recommending changes to staffing or outreach.

## Explore the work

[Read the original facility access report (PDF)](/documents/urec_facility_access.pdf).

The report is preserved as a historical artifact. Its figures have not been recomputed for this portfolio update.
