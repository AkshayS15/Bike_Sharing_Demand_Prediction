# Bike_Sharing_Demand_Prediction
## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
## CONCLUSION 
During the time of our analysis, we initially performed EDA on all of the features of dataset. We have analysed both numerical as well as categorical variables. For a good analysis we splitted the date column and added a new column as weekday_weekends. We also saw about the correlation and other relationships and found out that dew_point_temprature and temprature column are colinear and so we dropped the dew_point_temprature column. Also our output feature had some outliers value so we tried to fixed it by square rooting the values of output feature values.

Next we implemented 6 machine learning algorithms Linear Regression,lasso,ridge,elasticnet,decission tree and Random Forest We did hyperparameter tuning to improve our model performance. The results of our evaluation are:
		Model	MAE	MSE	RMSE	R2_score	Adjusted R2
Training set	0	Linear regression	4.474	35.078	5.923	0.772	0.77
1	Lasso regression	7.255	91.594	9.570	0.405	0.39
2	Ridge regression	4.474	35.078	5.923	0.772	0.77
3	Elastic net regression	5.792	57.574	7.588	0.626	0.62
4	Dicision tree regression	6.005	60.213	7.760	0.609	0.60
5	Random forest regression	0.810	1.600	1.265	0.990	0.99
Test set	0	Linear regression	4.410	33.275	5.768	0.789	0.78
1	Lasso regression	7.456	96.775	9.837	0.387	0.37
2	Ridge regression	4.410	33.277	5.769	0.789	0.78
3	Elastic net regression Test	5.874	59.451	7.710	0.624	0.62
4	Dicision tree regression	6.458	70.213	8.379	0.556	0.55
5	Random forest regression	2.204	12.732	3.568	0.919	0.92

- No overfitting is seen.
- Random forest Regressor gridsearchcv gives the highest R2 score of 99% for Train Set and 92% for Test set.
- We can deploy this model.
