+++
title = "Comparing electricity forecasts"
summary = "An R forecasting study comparing benchmarks, exponential smoothing, ARIMA, and ensembles for US fossil-fuel electricity generation."
date = "2024-05-10"
weight = 4
category = "Forecasting"
period = "Academic project"
layout = "detail"
tags = ["R", "Forecasting", "Model evaluation"]
showtoc = false
hideMeta = true
url = "/projects/fossil-fuel-forecast/"

[cover]
image = "/images/arima2_forecast.png"
alt = "Historical forecast of fossil-fuel electricity generation"
relative = false
hidden = true
+++

## The question

How did forecasts from simple benchmarks compare with more complex models of US electricity generation from fossil fuels?

## My contribution

I worked with annual observations from Our World in Data and used R to explore transformations, time-series patterns, residuals, and forecast accuracy. The report compares mean, naive, and drift benchmarks with exponential smoothing, ARIMA, and combinations of model forecasts.

## What the historical comparison showed

The report's final accuracy table ranks its model named "arima2" ahead of the other candidates. The naive method performs best among the simple benchmarks. These are results documented in the original report, rather than independently reproduced scores.

## What a new version would improve

The report's unit labels and transformations need verification against the source data. Its short annual series also limits confidence in a long forecast horizon. A stronger follow-up would use an explicit source snapshot, check units and model specifications, and compare forecasts across multiple historical cutoffs.

This project illustrates model comparison and communicating uncertainty. The old forecast is a historical exercise, not a current energy outlook.

## Explore the work

[Read the original forecasting report (PDF)](/documents/us_fossil_fuel_forecast.pdf).
