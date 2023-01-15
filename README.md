# Bike_Sharing_Demand_Prediction
## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
## CONCLUSION 
During the time of our analysis, we initially performed EDA on all of the features of dataset. We have analysed both numerical as well as categorical variables. For a good analysis we splitted the date column and added a new column as weekday_weekends. We also saw about the correlation and other relationships and found out that dew_point_temprature and temprature column are colinear and so we dropped the dew_point_temprature column. Also our output feature had some outliers value so we tried to fixed it by square rooting the values of output feature values.

Next we implemented 6 machine learning algorithms Linear Regression,lasso,ridge,elasticnet,decission tree and Random Forest We did hyperparameter tuning to improve our model performance. 
- No overfitting is seen.
- Random forest Regressor gridsearchcv gives the highest R2 score of 99% for Train Set and 92% for Test set.
- We can deploy this model.
