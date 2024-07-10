****Housing Price Prediction**
**

This repository contains a Python script for analyzing and predicting housing prices using a dataset from https://www.cia.gov/the-world-factbook/ .

**The script performs the following tasks:
**

**Data Loading and Exploration:**
Loads the housing data from a CSV file, displays the first few rows, and calculates basic statistics.

**Visualization:** 
Creates a scatter matrix and correlation heatmap to visualize relationships between features.

**Data Cleaning:**
Checks for missing values.

**Model Building and Evaluation:**
Splits the data into training and testing sets.
Implements a linear regression model with pipeline for preprocessing and evaluation.
Performs cross-validation to assess model performance.
Trains the model on the entire training set.
Evaluates the model on the testing set using mean squared error (MSE) and R-squared metrics.
Plots actual vs. predicted values.
Compares the performance of Ridge and Lasso regression models with linear regression.

**Feature Importance Analysis:**
Performs polynomial regression to identify important features.
Ranks features based on their importance in the polynomial regression model.
Visualizes the top 10 most important features using bar and pie charts.

**Libraries used:**
pandas
numpy
plotly.express
plotly.graph_objs
scikit-learn
