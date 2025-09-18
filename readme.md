# Bangalore Flats Price Prediction

## Overview
Machine learning project to predict flat prices in Bangalore using features like `location`, `total_sqft_num`, `bath`, `bhk`, and `price`. Built multiple regression models to compare performance and identify key price drivers.

---

##  Features
- **location**: Area (categorical)
- **total_sqft_num**: Flat size in sqft
- **bath**: Bathrooms
- **bhk**: Bedrooms
- **price**: Target (numeric)

---

##  Models
- **Linear Regression** – Baseline model.
- **Random Forest Regressor** – Better at capturing nonlinearity.
- **XGBoost Regressor** – Best accuracy overall.

---

##  Metrics
- **RMSE**
- **MAE**
- **R² Score**

---

##  Insights
- **Total square footage** and **location** are the strongest price drivers.
- **BHK** and **bathrooms** have moderate influence.
- **Tree-based models** outperform Linear Regression, highlighting nonlinear patterns.

---

## Impact
- Enables fair price benchmarking for buyers.
- Helps investors identify high-value areas.
- Demonstrates ML’s usefulness in real estate analytics.

---

## Author
Created as part of a machine learning portfolio project.