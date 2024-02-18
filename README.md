This ML Model has been built as a part of the Kaggle competition: Blue-Book for Bulldozers: https://www.kaggle.com/c/bluebook-for-bulldozers/
The objective of the project is to predict the prices of the Bull-dozers, by analysing and modelling a time series data.
The competition expects us to return the predicted prices for the year 2012, while the historic data given ranges over the years from 1900's to 2010's.
In this approach, I have used a RandomForestRegressor in order to fit the data, as it is a fairly large dataset, containing over a 4 million rows.
The RandomForestRegressor works fairly well for large datasets, since it is an ensemble model.
The dataset could be downloaded from here:https://github.com/mrdbourke/zero-to-mastery-ml/raw/master/data/bluebook-for-bulldozers.zip
