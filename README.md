# House price prediction with linear regression

A simple machine learning project that predicts house prices based on area features using Linear Regression.

## What it does

- Loads housing data (`usa_housing.csv`)
- Explores the data with pairplots, distribution plots, and a correlation heatmap
- Trains a Linear Regression model to predict house price
- Evaluates the model using MAE, MSE, and RMSE

## Features used

- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population

## Requirements

```
pandas
numpy
seaborn
matplotlib
scikit-learn
```

Install with:
```
pip install pandas numpy seaborn matplotlib scikit-learn
```

## How to run

1. Place `usa_housing.csv` in the same folder as the notebook.
2. Open `House_Price_Prediction_with_Linear_Regression.ipynb` in Jupyter.
3. Run all cells from top to bottom.

## Output

The model prints its intercept, feature coefficients, and evaluation metrics (MAE, MSE, RMSE), along with plots comparing actual vs. predicted prices.
