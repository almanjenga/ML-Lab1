# Office Price Prediction using Linear Regression

This project uses linear regression with gradient descent to predict office prices based on office size. We train the model on data from an Excel file, `Nairobi_office_price.csv`, which contains office sizes and their respective prices.

## Project Description

The project is designed to:
1. Load and preprocess data from the provided dataset.
2. Train a linear regression model using gradient descent.
3. Track the model's Mean Squared Error (MSE) across epochs to monitor training performance.
4. Plot the final line of best fit alongside the data points.
5. Predict the price of an office based on a specified size (e.g., 100 sq. ft).

## Dataset

The dataset `Nairobi Office Price Ex.csv` has two required columns:
- **SIZE**: The size of the office in square feet.
- **PRICE**: The target variable representing the price of the office.


## Requirements

numpy
pandas
matpotlib
