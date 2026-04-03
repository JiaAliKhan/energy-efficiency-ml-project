Energy Efficiency Prediction using Machine Learning
Project Overview

This project applies machine learning techniques to predict building energy efficiency based on architectural design parameters. The goal is to analyze how different building characteristics influence heating and cooling load requirements.

The project uses the Energy Efficiency dataset and implements several machine learning regression models to predict energy consumption.

Objectives
Analyze the Energy Efficiency dataset
Perform Exploratory Data Analysis (EDA)
Apply multiple machine learning algorithms
Compare model performance
Predict heating and cooling load values
Dataset

The dataset used in this project is the Energy Efficiency dataset, which contains information about building design parameters.

Features include:

 Relative Compactness
Surface Area
Wall Area
Roof Area
Overall Height
Orientation
Glazing Area
Glazing Area Distribution

Target variables:

Y1 – Heating Load
Y2 – Cooling Load
Machine Learning Models Used

The following models were implemented:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Support Vector Regression (SVR)
K-Nearest Neighbors Regressor
Exploratory Data Analysis

Several visualizations were created to understand the dataset:

Histograms
Correlation Heatmap
Pairplots
Distribution plots
Scatter plots for predicted vs actual values
Model Evaluation

The models were evaluated using regression metrics:

R² Score
Mean Squared Error (MSE)

Graphs were also used to compare actual and predicted values.

Results

Among the tested models, ensemble-based methods such as Random Forest generally provided strong predictive performance due to their ability to capture complex relationships in the data.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Author

Nadia Bibi

Machine Learning Project – Energy Efficiency Prediction
