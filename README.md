# Nebraska K-12 Chronic Absenteeism Prediction

**DSCI/STAT 8950 — Data Science Capstone | UNO Spring 2026**  
**School-Level Analysis — Nilesh Purnekar**

## Project Overview
Predicting chronic absenteeism rates across Nebraska K-12 schools 
using socioeconomic factors (Free & Reduced Lunch %) over 7 years 
(2018-2025) across 73 schools in 10 counties.

## Repository Structure

### Capstone Project — Final Submission
- `Capstone_very_Fianl.ipynb` — Original: Feature engineering, ML models, results (Steps 1-26)
- `Capstone_very_Fianl_ipynb_Feedback.ipynb` — Updated based on professor feedback: CV RMSE vs Test RMSE overfitting detection and CV R² for model selection (Steps 27-30)
- `Nilesh_Purnekar_individual_Report.pdf` — Final Individual Capstone Report
- `Nebraska_Absenteeism_FINAL_Espresso_1.pptx` — Final Capstone Presentation (Abhinav Adhikari + Nilesh Purnekar)

### EDA
- `preprocessing_&_merging.ipynb` — Data loading, cleaning, merging (14 raw files → 2 datasets)
- `EDA.ipynb` — Exploratory data analysis with 13 charts and visualizations
- `Individual_EDA_FRL_Absenteeism_0_35856800_1771353622 (2).html` — Individual EDA Report (HTML)
- `Nebraska_EDA_TeamB (1).pptx` — EDA Team Presentation

### Datasets
- `final_panel_dataset.csv` — Cleaned panel dataset (8,444 rows, 1,298 schools, 7 years)
- `final_ML_dataset.csv` — ML-ready dataset with target variable (361 rows, 73 schools)

### Literature Survey
- `Literature_survey.pptx.pdf` — Literature Survey Presentation

### ML Independent Study
- `ML_Applications(Individual) (1).ipynb` — Advanced ML Applications Individual Study
- `ML_Independent_study (1).zip` — ML CNN Independent Study

### Other Presentations
- `TeamB_Combined_Presentation (1).pptx` — Team B Combined EDA Presentation

## Key Results
XGBoost Default — Best Model
- Test R² = 0.8143
- Test RMSE = 0.0389
- CV R² = 0.6441
- MAE = 0.0249

## Data Source
Nebraska Department of Education (NDE) — publicly available  
https://www.education.ne.gov/

## Course
DSCI/STAT 8950 — Data Science Capstone  
University of Nebraska Omaha | Spring 2026
