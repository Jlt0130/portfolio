+++
title = "Torpedo Bats: Modeling Expected Offensive Performance"
summary = "Python regression analysis exploring how bat speed and launch metrics predict xwOBA performance among MLB hitters."
date = "2024-09-10"
tags = ["Python", "Regression", "Sports Analytics"]
showtoc = false
hideMeta = true
url = "/projects/torpedo-bats-regression/"

[cover]
  image = "/images/projects/torpedo-bats/cover.png"
  alt   = "Baseball analytics regression visualization"
  relative = false
+++

**What I did**
- Imported and cleaned MLB Statcast datasets using pandas and numpy.
- Engineered predictive variables (average exit velocity, launch angle variance, hard-hit rate).
- Built and evaluated multiple regression models in statsmodels to estimate xwOBA.
- Interpreted coefficients to identify the metrics most associated with high offensive production.
- Visualized regression fits and residuals with matplotlib and seaborn.

**Results**
- Identified bat speed and hard-hit rate as the strongest predictors of expected wOBA.
- Created model with adjusted R² ≈ 0.82 and statistically significant coefficients (p < 0.05).
- Highlighted 10 top-performing hitters whose actual performance outpaced model predictions, offering potential scouting insights.

**Tools Used**
- Python, pandas, numpy, statsmodels, matplotlib, seaborn

**Links**
- [GitHub Repo](#)
- [Notebook (HTML)](#)
- [PDF Report](/documents/torpedo_bats.pdf)