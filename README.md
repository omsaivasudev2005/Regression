ABOUT DATASET
Source: Kaggle
Features:id,date,price,bedrooms,bathrooms,sqft_living,sqft_lot,floors,waterfront,view,condition,grade,sqft_above,sqft_basement,yr_built,yr_renovated,zipcode,lat,long,sqft_living15,sqft_lot15
size:21613 rows,21 columns

WHAT I DID
--Found no null values
--Dropped unnecessary columns
--Transformed skewed data using cbrt,log transformations
--Performed OLS
--Found correlation between independent features 
--Due to correlation, we were getting inaccurate results
--Used regularization techniques for feature selection like Lasso,Ridge,ElasticNet
--Used GridSearchCV to perform these techniques among various combinations
--Found best parameters and scores of each technique
--As the result was not satisfying, used few bagging and boosting techniques
--They outperformed previous models
--XGBoost Regressor performed well with an r2_score of (87%)
