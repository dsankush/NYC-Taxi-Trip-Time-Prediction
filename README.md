# NYC_Taxi_Trip_Time_Prediction_Capstone_Project
Build a model that predicts the total ride duration of taxi trips in New York City
Problem Description
Your task is to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.
Data Description
The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set.
NYC Taxi Data.csv - the training set (contains 1458644 trip records)

# Conclusion :

We can observe that we have applied multiple models with different approaches and we can clearly see that in all cases XGBOOST was working very fine other than Decision Tree and Random Forest Regression

But after implementing the PCA to our features and we successfuly reduced our feature dimension and we observed that after transformation Decision Tree and Random Forest is also doing great job even far better that without transformation

And also XGBOOST is also working better after PCA transformation and also XGBOOST is also showing slightly better scores in terms of RMSE | MSE which is lesser than other models and also R2 | Adj R2 scores are also not having that much difference and also higher than other models.

So our conclusion from this whole analysis is that we can go with XGBOOST Regressor to get Good Prediction rate and lesser Error prone and also it can be more optimized using more tuned hyperparameters.

# Future Work :

As this data set is of only almost 6 months and I think there should be more data for more than a year and also some more features should be there so that we can train our models with more significant information that will help our model to learn more efficiently so that we can get more higher performance from Machine Learning Models

And also we can extract more information about this data by getting more features so that we can explore more about this kind of data
