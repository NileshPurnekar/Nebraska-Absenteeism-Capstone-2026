# Nebraska K-12 Chronic Absenteeism Prediction

**DSCI/STAT 8950 — Data Science Capstone | UNO Spring 2026**
**School-Level Analysis — Nilesh Purnekar**

## Project Overview
Predicting chronic absenteeism rates across Nebraska K-12 schools 
using socioeconomic factors (Free & Reduced Lunch %) over 7 years 
(2018-2025) across 73 schools in 10 counties.

## Files
- `preprocessing_&_merging.ipynb` — Data loading, cleaning, merging
- `EDA.ipynb` — Exploratory data analysis
- `Capstone_very_Fianl.ipynb` — Original: Feature engineering, ML models, results (Steps 1-26)
- `Capstone_very_Fianl_ipynb_Feedback.ipynb` — Updated based on professor feedback: Added CV RMSE vs Test RMSE overfitting detection and CV R² for model selection (Steps 27-30)

## Key Results
XGBoost Default — Best Model
- Test R² = 0.8143
- Test RMSE = 0.0389
- CV R² = 0.6441
- MAE = 0.0249

## Data Source
Nebraska Department of Education (NDE) — publicly available
https://www.education.ne.gov/
