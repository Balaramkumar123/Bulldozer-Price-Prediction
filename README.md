This ML Model has been built as a part of the Kaggle competition: Blue-Book for Bulldozers: https://www.kaggle.com/c/bluebook-for-bulldozers/ .
The objective of the project is to predict the prices of the Bull-dozers, by analysing and modelling a time series data.
The competition expects us to return the predicted prices for the year 2012, while the historic data given ranges over the years from 1900's to 2010's.
The competition evaluates the model based on Root Mean Log Squared Error (RMLSE) metric.
In this approach, I have used a RandomForestRegressor in order to fit the data, as it is a fairly large dataset, containing over a 4 million rows.
The RandomForestRegressor works fairly well for large datasets, since it is an ensemble model. 
This competition was live in 2013, but I came across it recently and was interested in it. 
The winner had a RMLSE value of 0.22, while our model's validation RMLSE is close to 0.24. 
this indicates that our model has done fairly well compared to most of the participants. 
The dataset could be downloaded from here:https://github.com/mrdbourke/zero-to-mastery-ml/raw/master/data/bluebook-for-bulldozers.zip
