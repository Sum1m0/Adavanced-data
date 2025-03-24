# Stock Market Prediction

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Aim and Objectives](#aim-and-objectives)
4. [Technologies Used](#technologies-used)
5. [Dataset](#dataset)
6. [Models Implemented](#models-implemented)
7. [Evaluation Metrics](#evaluation-metrics)
8. [Usage](#usage)

## Introduction

The stock market plays a crucial role in global economies, and accurate prediction of stock prices is a valuable asset for investors. This project seeks to leverage machine learning techniques to enhance prediction accuracy and assist in informed decision-making.

## Problem Statement

The project addresses the challenge of predicting stock market trends using machine learning models, given the complex and volatile nature of the market. Prior studies have often focused on limited methods, creating a need for comparative analysis of diverse approaches to improve prediction accuracy.

## Aim and Objectives

### Aim
To perform an in-depth comparative analysis of various machine learning models for stock market prediction, with the goal of enhancing prediction accuracy and understanding model effectiveness.

### Objectives
- Conduct a comprehensive literature review on stock market prediction.
- Explore optimal data preprocessing techniques.
- Evaluate machine learning models (ARIMA, LSTM, TCN, and so on) for predicting stock prices.
- Compare performance metrics to determine the most effective model.

## Technologies Used

- **Python**: Main programming language.
- **Jupyter Notebook**: For data analysis and visualization.
- **PyCharm**: IDE for model implementation and code management.
- **Libraries**:
  - `TensorFlow` for deep learning models.
  - `NumPy` for numerical computations.
  - `Pandas` for data manipulation.
  - `Scikit-learn` for data preprocessing and evaluation.
  - `Keras` for building deep learning models.

## Dataset

The dataset was sourced from Yahoo Finance, using the `yfinance` Python library. It includes historical and real-time stock market data such as prices and trading volumes.

## Models Implemented

1. **ARIMA**: Used for modeling linear relationships and stationary data.
2. **LSTM**: Suitable for capturing long-term dependencies in sequential data.
3. **TCN**: Effective for managing complex patterns and high-frequency trends.
4. **Decision Tree Regression**: a non-parametric algorithm, that can handle non-linear relationships and offers high interpretability
5. **Linear Regression**: a fundamental statistical method, that aims to establish a linear relationship between independent and dependent variables by minimizing the mean squared error,
6. **Meta Prophet**: a powerful time - series forecasting tool that can automatically decompose time series into components like trends, seasonality, and holiday effects, providing reliable predictions in various business scenarios.

## Evaluation Metrics

The performance of the models is evaluated using:
- **MAPE (Mean Absolute Percentage Error)**
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**


## Usage

1. Run the Jupyter Notebook to explore data analysis and model training:
    ```bash
    jupyter notebook
    ```
2. Import the files `*.ipynb ` into your jupyter notebook terminal, and run the files
