# Project-4---Store-Sales-ML
To create a machine learning model to project store sales
Project 4 - Store Sales Prediction
Source: https://www.kaggle.com/datasets/surajjha101/stores-area-and-sales-data

Goal: To use the 3 variables to predict the future sales of a store based on (store sq. yd., # of items, and traffic). 

Steps/Outline
Import csv
Convert the data over to a data frame
Add a column to show adjusting from yards Sales $ per sq. ft. 
Clean the data frame, removing nulls
Do an elbow curve to find the number of bins
Building a binning to categorize the stores by the different metric (clustering)
Use Pyspark SQL to better understand the clusters
Split data into train and test
Run Linear regression model with scaled x & y data
Get accuracy score
Plotly/Matplot the actuals vs. predicted
Run the KNN model with a couple of variations with different to optimize the accuracy score
Plotly/Matplot the actuals vs. predicted


Slides
Data set Introduction- Process/Outline (adding columns, clustering, 4 models (Linear, random forest, xgb, and KNN)- Nick
Distribution curves - pointing to items/sqft was the only thing linear- Trevor
Show sns plot with feature correlation- Nick
Results from the 4 model- Trevor
Summary - Data wasn’t good - Nick

Summary

