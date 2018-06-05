# Kaggle---Retail-Case-Study
Sales forecast for a major US Retailer. Secured  second rank. 

Given datasets about Sales, Macroeconomics, Weather and Holidays, predict sales for next year. 

Evaluation Metric - RMS


### Data Preprocessing - 

1.Imputation

2.Given weather data was broken down to days and all other data was in months. So converted the weather data to months by making valid assumptions.

3.Numeric encoding for categorical features 'month' and 'category'

4.Features selection and feature engineering


### Representation - 

Adopting CART to map input values to output vaulues.


### Training - 

Tried out Decison trees, Random Forest regressor, Adaboost regressor and Gradient Boosting Regressor.


### Evaluating - 

Best RMS score was given by Gradient Boosting Regressor. 

