# Polynomial Regression

This repository contains code for implementing polynomial regression on a dataset of position levels and corresponding salaries. The code is written in Python and uses the scikit-learn library.

## Code Explanation

The code performs the following steps:

1. Imports the required libraries: numpy, matplotlib, and pandas.
2. Reads the dataset from a CSV file named `Position_Salaries.csv`.
3. Separates the independent variable (position level) and the dependent variable (salary) from the dataset.
4. Trains a linear regression model on the entire dataset.
5. Trains a polynomial regression model with a degree of 4 on the entire dataset.
6. Visualizes the results of both the linear regression and polynomial regression models using scatter plots and line plots.
7. Generates a higher resolution and smoother curve for the polynomial regression model by creating a grid of position levels.
8. Demonstrates how to predict a new salary using both the linear regression and polynomial regression models for a position level of 6.5.

## Dataset

The dataset used in this code is included in the repository and named `Position_Salaries.csv`. It contains the following columns:

| Position Level | Salary |
| -------------- | ------ |
| 2              | 45000  |
| 3              | 50000  |
| 4              | 60000  |
| 5              | 80000  |
| 6              | 110000 |
| 7              | 150000 |
| 8              | 200000 |
| 9              | 300000 |
| 10             | 500000 |
| 11             | 1000000|

The `Position Level` column represents the level of the position, and the `Salary` column represents the corresponding salary for that position level.

## Usage

To run the code, you need to have Python and the required libraries installed. You can install the necessary libraries using pip:
After installing the required libraries, you can run the code by executing the Python script.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
