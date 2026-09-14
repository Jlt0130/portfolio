+++
title = "Bat speed and offensive performance"
summary = "A collaborative Python regression project exploring bat speed, contact quality, and the interpretation of hypothetical performance changes."
date = "2025-05-01"
weight = 5
category = "Sports analytics"
period = "Spring 2025"
layout = "detail"
tags = ["Python", "Regression", "Sports analytics"]
showtoc = false
hideMeta = true
url = "/projects/torpedo-bats-regression/"

[cover]
image = "/images/torpedo_bats_regression.png"
alt = "Historical comparison of predicted and observed xwOBA"
relative = false
hidden = true
+++

**Collaborative project with Skyler Strzelecki · Spring 2025**

## The question

How are bat speed and squared-up rate associated with expected weighted on-base average (xwOBA), and how should a hypothetical increase in bat speed be interpreted?

## The project

Our project used Baseball Savant data and a Python regression workflow to compare observed and predicted xwOBA. The report explored a scenario in which bat speed increases by three miles per hour while contact quality is held constant.

## An important modeling limitation

The report specifies an additive linear model. In that model, changing every player's bat speed by the same amount while holding the other predictor fixed should produce the same change in the model's prediction.

The report nevertheless presents different player gains and losses. Those comparisons need an audit of the original calculation and prediction baseline. They should not be interpreted as validated evidence of who benefits most from a particular bat.

The project remains a useful example of regression, collaborative analysis, and the distinction between a hypothetical scenario and a demonstrated equipment effect.

## Explore the work

[Read the original coauthored report (PDF)](/documents/torpedo_bats.pdf).
