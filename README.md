# Cake Price Prediction Project

## Overview
This project aims to predict cake prices based on various features such as size, ingredients cost, design complexity, and more. It uses machine learning techniques to analyze historical data and create a model that can estimate cake prices for new inputs.

## Features
- Data cleaning and preprocessing
- Feature selection and engineering
- Machine learning model (Random Forest Regressor)
- Price prediction functionality

## Dataset
The dataset includes the following features:
- Sold_On: Day of the week
- Size: Cake size (small, medium, large)
- Ingredients_Cost: Cost of ingredients
- Design_Complexity: Complexity of the cake design
- Time_Taken: Time taken to make the cake (in hours)
- Amount: Number of similar cakes sold in the same order
- Gender: Gender of the person ordering the cake(s)
- Price: The price of the cake (target variable)

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn

## Usage
1. Ensure all required libraries are installed.
2. Run the Jupyter notebook `cakepriceprediction.ipynb` to see the full analysis and model development process.
3. Use the `predict_cake_price()` function to make predictions for new cake orders.

## Model Performance
The Random Forest Regressor model achieved the following performance metrics:
- Root Mean Squared Error (RMSE): [Insert value]
- R-squared Score: [Insert value]

## Future Improvements
- Collect more data to improve model robustness
- Experiment with other machine learning algorithms
- Fine-tune model hyperparameters
- Develop a user-friendly interface for price predictions

