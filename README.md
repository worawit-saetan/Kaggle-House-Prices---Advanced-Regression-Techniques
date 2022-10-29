# Kaggle-House-Prices---Advanced-Regression-Techniques

Predict sales prices and practice feature engineering, RFs, and gradient boosting

## The outline is as follows
+ read the the dataset and split it into training and test set
+ check and fill in missing data
+ encode columns with one hot encoder
+ scaling the target value with Log10 (cheap and expensive houses will affect the result equally)
+ train our XGBoost model with GridSearchCV and test its score on test set
+ train another XGBoost model with manual setting and test its score on test set
+ train another XGBoost model with the same manual setting on merged train-test set (train with more data)
+ sent our models' predictions to Kaggle
