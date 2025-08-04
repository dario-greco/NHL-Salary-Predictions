# NHL Salary Prediction – Regression Ensemble

This project explores machine learning methods for predicting NHL player salaries using player performance and team-level data. Developed for a Kaggle-hosted competition at the University of Waterloo, the final model achieved **2nd place** on the public leaderboard.

## Summary

The analysis focused on engineering meaningful features, transforming the target variable (log-salary), and comparing several regression models. Tree-based methods performed best, and the final prediction was formed by averaging multiple high-performing models.

## Methods Used

- Exploratory data analysis and preprocessing
- Feature engineering (e.g., point-per-minute, cap-efficiency ratios)
- Log-transform of the response variable
- Model tuning with `caret`
- Ensemble of the following models:
  - Generalized Additive Models (GAM)
  - Gradient Boosting Machines (GBM)
  - Random Forest
  - XGBoost

## Files

- `NHL_Salary_Model.Rmd` – Full model development and evaluation in RMarkdown
- `report.pdf` – Exported summary report

## Tools

- R (tidyverse, caret, gbm, xgboost, mgcv)
- RMarkdown

## Result

- 2nd place on the public leaderboard  
- Final solution formed by averaging predictions from four tree-based models  
- Leaderboard: [Kaggle Competition – Advanced Regression](https://www.kaggle.com/competitions/adv-regression/leaderboard)
