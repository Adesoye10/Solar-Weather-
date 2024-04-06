Solar Weather Data Analysis
Overview

This project is focused on analyzing solar weather data to predict temperature variables using various regression models. It demonstrates the entire data science process from data preprocessing, exploratory data analysis (EDA), model building, hyperparameter tuning, to model evaluation. The project employs several machine learning algorithms, including Decision Tree, Random Forest, AdaBoost, Gradient Boosting, XGBoost, and a Stacking Ensemble model to ensure the highest prediction accuracy.
Features

    Data Preprocessing: Includes handling of missing values, outliers, and normalization of column names.
    Exploratory Data Analysis (EDA): Utilizes histograms, boxplots, and heatmaps to understand the data distribution and feature correlations.
    Model Building and Evaluation: Implements various regression models and evaluates them based on RMSE, MAE, R-squared, and Adjusted R-squared metrics.
    Hyperparameter Tuning: Applies GridSearchCV for tuning models to improve performance.
    Feature Importance Visualization: Offers insights into the most significant features for each model.
    Stacking Ensemble Model: Combines predictions from multiple models to enhance the predictive power.

Installation

To run this project, you need to have Python installed on your machine. After cloning the repository, install the required dependencies:

bash

pip install -r requirements.txt

Usage

To execute the analysis, navigate to the project directory and run the main script:

bash

python solar_weather_analysis.py

Ensure you have the solar weather dataset solar_weather.csv in the project directory or update the script with the correct path to your dataset.
