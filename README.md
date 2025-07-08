# EV-Sales-Data-Analysis-Project

## Project Overview

This project analyzes Electric Vehicle (EV) sales trends across Indian states and builds a predictive model to forecast future demand. Using machine learning (Random Forest Regression), it identifies key drivers of EV adoption, such as state policies, vehicle types, and temporal trends.

--- 

## Why This Matters
This project helps automakers, policymakers, and investors optimize strategies for India’s booming EV market.

**Tech Stack:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## Key Features
**Data Cleaning & Feature Engineering:**

* Extracted month/day from dates for time-series analysis.

* Encoded categorical variables (State, Vehicle_Class) via one-hot encoding.

**Machine Learning Modeling:**

* Random Forest Regressor (R² = 0.93, MAE = 11 units).

* Time-based validation to prevent future data leakage.

**Visualizations & Insights:**

* Top states: UP, MH, KA drive 65% of sales.

* Vehicle preference: 2-wheelers (48%) > e-rickshaws (30%) > cars (15%).

* Growth trends: 45% CAGR post-2020 (policy impact).

**Model Diagnostics:**

* Residual plots reveal underestimation at peak demand.

* Feature importance highlights Year, State, and Vehicle_Class as top predictors.

---
