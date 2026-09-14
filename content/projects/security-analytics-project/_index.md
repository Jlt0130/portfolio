+++
title = "Investigating patterns in security logs"
summary = "A Splunk coursework investigation using queries, timelines, and dashboards to examine suspicious activity in a training dataset."
date = "2025-02-10"
weight = 7
category = "Security analytics"
period = "Coursework"
layout = "detail"
tags = ["Splunk", "SPL", "Log analysis"]
showtoc = false
hideMeta = true
url = "/projects/security-analytics/"

[cover]
image = "/images/security_analytics_cover.png"
alt = "Historical Splunk security analysis dashboard"
relative = false
hidden = true
+++

## The question

What patterns in a training log dataset warrant further investigation, and how can the supporting evidence be organized?

## My contribution

I wrote Splunk Processing Language queries to examine failed logins, injection indicators, privilege-related events, transfer volumes, and bot activity. I organized the findings into a query report and a dashboard showing counts and activity over time.

## Interpreting the evidence

The work demonstrates filtering, aggregation, and investigation across event types. Similar timestamps or event counts do not alone establish a coordinated attack, and a large transfer does not alone prove successful data theft.

The original report contains stronger interpretations that would need additional evidence. This is a historical coursework exercise, not an incident at my employer.

## Explore the work

- [Read the original query report (PDF)](/documents/security_analytics_splunk.pdf)
- [View the dashboard (PDF)](/documents/security_analytics_dashboard.pdf)
