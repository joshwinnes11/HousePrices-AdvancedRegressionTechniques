# House Prices - Advanced Regression Techniques
### Josh Winnes
### August 4, 2024
This repository contains notebooks for the Kaggle beginner competition *'House Prices - Advanced Regression Techniques.'* `walkthrough.ipynb` is heavily inspired by a YouTube walkthrough by Ryan Nolan, though I made adjustments to his work in order to try and improve his models. The training and testing data are uploaded as `train.csv` and  `test.csv` respectively. My model scored 0.12737 (RMSE) which, at the time of submission (August 4, 2024) was good enough for 664th place out of 23,804 submissions landing my model in the 97th percentile.

## **walkthrough.ipynb**
This notebook tests various regression models including:
- `sklearn.linear_model.LinearRegression`
- `sklearn.linear_model.Ridge`
- `sklearn.ensemble.RandomForestRegressor`
- `sklearn.ensemble.GradientBoostingRegressor`
- `sklearn.ensemble.StackingRegressor`
- `sklearn.ensemble.VotingRegressor`
- `xgboost.XGBRegressor`
- `catboost.CatBoostRegressor`
- `lightgbm.LGBMRegressor`
The RMSE of the final model is 0.12737 (97th percentile)
