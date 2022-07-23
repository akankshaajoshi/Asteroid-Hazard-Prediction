# Asteroid-Hazard-Prediction
A random forest classifier asteroid hazard prediction model with an accuracy of 94.8%. 

Dataset for this project is picked from Kaggle. It includes data of NASA's classified nearest earth objects - primarily asteroids. 
Dataset: https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects Download using the API Call: kaggle datasets download -d sameepvani/nasa-nearest-earth-objects

Asteroid hazard prediction is a random forest classifier based model which uses NASA's dataset on nearest earth objects to predict the hazardous or non-hazardous nature of asteroids . Methodologies and approaches applied in this project are:

1.Data wrangling: Unreleated features(with very low correlation coefficients) were dropped and features with low feature importances were removed to simplify the model. Data with duplicated indices were dropped to avoid any complications.

2.EDA (Exploratory data analysis): Infographics were created using PyPlot and Seaborn to understand the relationship among data variables. Heatmaps describing the correlation between variables, histplots, pairplots, data descriptions and value counts for different data provided information regarding the dataset.

3.Prediction model: The model uses Synthetic Minority Oversampling to handle the prevalent class imbalance in the dataset. Classification methods such as logistic regression, decision tree, random forests and xgboost were tested to check the best model performance . 

4.Model evaluation: 

An overall R2 Metric for the test data came out to be 81.5% for the test set and that for 4-fold validation test is given in the .ipynb file.
