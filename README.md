# Logistic-Regression-Model
Co-authors: 
* AndreasAAU420: https://github.com/AndreasAAU420 
* MrKahr: https://github.com/MrKahr 
* SweetAndJuicy: https://github.com/SweetAndJuicy
* ThorSkatka: https://github.com/ThorSkatka

## Overview
This model is an ongoing project in the making for a data science BA course at Aalborg University. 
A logistic regression model that predicts if an olympic athlete wins a medal. The data the model trains with, is in the form of pandas dataframes and comes from a CSV-file "athlete_events.csv" with stats on all athletes participating in the modern olympics: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results.

## How to use
* The file OL_logistic_regression_model.ipynb is used to plot a ROC-curve of the different cut of points for the model, and finds the optimal value for the binary classification of the athletes.
* The file marked with 01 is used to apply suplimentary columns to the dataframe, and to prepair it for the model.
* The file marked with 02 is the model, and trains on the dataframe it is given.
