# Regression-Analysis

This repository contains Jupyter Notebooks demonstrating various regression analysis techniques using Python. Each notebook focuses on a specific type of regression and includes examples with relevant datasets.

## Overview

This collection of notebooks covers the following regression methods:

* **Simple Linear Regression:** Explores the relationship between a single independent and dependent variable.
* **Multiple Linear Regression:** Predicts a dependent variable using two or more independent variables.
* **Polynomial Regression:** Models non-linear relationships by fitting a polynomial curve to the data.
* **Exponential Regression:** Analyzes relationships where the dependent variable changes exponentially with the independent variable.
* **Logistic Regression:** Although technically a classification algorithm, this notebook demonstrates how it's used to predict binary outcomes.

## Notebook Contents

1.  **`Simple Linear Regression.ipynb`**:
    * Demonstrates simple linear regression using the `computers.csv` dataset.
    * Includes steps for data loading, visualization, model building (using `scikit-learn`), and evaluation.

2.  **`MultipleLinearRegression.ipynb`**:
    * Illustrates multiple linear regression with the `delivery.csv` dataset.
    * Covers data preprocessing, model training (using `statsmodels` or `scikit-learn`), and interpretation of results.

3.  **`Polynomial Regression.ipynb`**:
    * Explores polynomial regression using the `Trees.csv` dataset.
    * Shows how to create polynomial features and fit a linear model to capture non-linear patterns.

4.  **`ExponentialRegression.ipynb`**:
    * Demonstrates exponential regression using the `Tire_useability.csv` dataset.
    * Focuses on fitting an exponential curve to the data using optimization techniques.

5.  **`logisticregression.ipynb`**:
    * Covers logistic regression for binary classification using the `defaulter.csv` dataset.
    * Includes steps for model building (using `scikit-learn`), prediction, and evaluation using metrics like the confusion matrix.

6.  **`Regression Analysis.ipynb`**:
    * Provides a basic introduction to regression analysis concepts, with a simple illustrative example using the "Units" and "Minutes" data.

## Datasets

The following datasets are used in these notebooks:

* `computers.csv`: Contains data for simple linear regression (repair time vs. number of units).
* `delivery.csv`: Contains data for multiple linear regression (delivery time and related factors).
* `Trees.csv`: Contains measurements of trees for polynomial regression analysis.
* `Tire_useability.csv`: Contains data on tire useability for exponential regression.
* `defaulter.csv`: Contains data for logistic regression (predicting default).
* (Data within `Regression Analysis.ipynb` for a basic example).

## Libraries Used

The notebooks in this repository utilize the following Python libraries:

* `pandas`: For data manipulation and analysis.
* `numpy`: For numerical computations.
* `matplotlib`: For creating static, interactive, and animated visualizations.
* `seaborn`: For making statistical graphics in Python.
* `scikit-learn`: For machine learning algorithms, including linear and logistic regression, and model evaluation.
* `statsmodels`: For statistical modeling, including linear regression analysis.
* `scipy`: For scientific and technical computing, used for curve fitting in exponential regression.

## Getting Started

To run these notebooks, you will need to have Python installed on your system along with the libraries listed above. You can install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels scipy
