# Boston Housing Price Prediction

## Overview
This project predicts house prices in Boston using the [Boston Housing Dataset](https://www.kaggle.com/c/boston-housing) from Kaggle. It uses machine learning models to analyze features like crime rate, number of rooms, and tax rates to estimate house prices.

## Dataset
- Download the [Boston Housing Dataset](https://www.kaggle.com/c/boston-housing) (`housing.csv`) from Kaggle.
- Place it in the `data/` folder.

## Description
Housing Values in Suburbs of Boston
--> The medv variable is the target variable.

# Data description
The Boston data frame has 506 rows and 14 columns.

This data frame contains the following columns:

- crim
per capita crime rate by town.

- zn
proportion of residential land zoned for lots over 25,000 sq.ft.

- indus
proportion of non-retail business acres per town.

- chas
Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).

- nox
nitrogen oxides concentration (parts per 10 million).

- rm
average number of rooms per dwelling.

- age
proportion of owner-occupied units built prior to 1940.

- dis
weighted mean of distances to five Boston employment centres.

- rad
index of accessibility to radial highways.

- tax
full-value property-tax rate per $10,000.

- lstat
lower status of the population (percent).

- medv
median value of owner-occupied homes in $1000s.


## Project Structure
- `data/`: Place `housing.csv` here (not uploaded).
- `notebooks/`: Jupyter notebooks for exploration and training.
- `requirements.txt`: Python dependencies.
- `README.md`: This file.

## Requirements
- Python 3.8+
- Libraries: `pandas`, `scikit-learn`, `numpy`, `jupyter` 

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/boston-housing-price-prediction.git
   cd boston-housing-price-prediction

pip install -r requirements.txt
Add housing.csv to data/.
