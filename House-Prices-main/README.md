# House-Prices
Predicting Iowa House Prices

## Overview
This notebook predicts house prices using a dataset of Iowa Houses and a Linear Regression model.

## Dependencies
- `numpy`
- `pandas`
- `sklearn`
- `matplotlib`

## Features Used
Some of the features used in the model include:
- **OverallQual**: Overall material and finish quality of the house.
- **GrLivArea**: Above-ground living area size in square feet.
- **GarageCars**: Number of cars the garage can hold.
- **GarageArea**: Size of the garage in square feet.
- **TotalBsmtSF**: Total basement area in square feet.
- **YearBuilt**: Year the house was built.
- **LotArea**: Lot size in square feet.

## Usage
1. Add `train.csv` to the same folder as this notebook.
2. Open the notebook and run all the cells.

## Results
The model predicts house prices and shows its performance with metrics like:
- **RMSE**: ~39,830
- **MAE**: ~24,678
