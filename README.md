# Payment-Date-Prediction-Model

Predicting payment_date on a dataset of 50000 rows using Linear Regression Algorithm.

# Importing the dataset
-using google colab

# PreProcessing the data
- dropping null and duplicate values
- dropping columns with high correlation value
- sorting the data according to create_date
- splitting the data into null and not null valued sub-sets on the basis of target column

# EDA (exploratory data analysis) on the train set
- scatter plot
- distribution plot

# Feature Engineering
- label encoding the values in a language that the model can use  to make predictions
- extracting date, month, year from date-type columns in int format

# Feature selection
- plotting heat map to correlation of features

# Data Modelling & Model Evaluation
- using Linear Regression, Tree based and XGBoost to fit the train set
- Linear Regression model used since input-ouput is numeric

# Final Prediction on Test set
- merged the predicted delay with test set
- created buckets for final payment date
