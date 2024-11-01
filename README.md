# MeXE402 - Mechatronics Engineering Elective 2: Data Science and Machine Learning 
## Pair-Based Midterm Project - Linear and Logistic Regression Analysis

## Introduction

This project demonstrates the application of two fundamental supervised machine learning algorithms **Linear Regression** and **Logistic Regression** used for predictive modeling.

- **Linear Regression** is employed to predict continuous outcomes by establishing a linear relationship between the dependent and independent variables.
- **Logistic Regression** is a classification algorithm used to model the probability of a binary outcome, typically for categorizing data into distinct classes.

The project is divided into two parts, each addressing different datasets and objectives.

## Dataset Description

### 1. **Stock Price Data of Apple Inc. (Linear Regression)**:
https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset 
   - This dataset contains historical stock prices of Apple Inc., includes the following variables: `Open`, `High`, `Low`, `Close`, `Adj Close`, and `Volume`.
     
        - Date: This is the trading date for the given stock data entry. It helps keep track of the sequence of trading days and is essential for time-series analysis.

        - Open: This is the price at which the stock was first traded when the market opened on that day. The opening price often reflects any changes or news that occurred after the previous day’s close.

        - High: The highest price at which the stock was traded during that specific trading day. It indicates the maximum value investors were willing to pay that day.

        - Low: The lowest price at which the stock was traded during the trading day. It shows the minimum value at which the stock traded and can indicate any dips in investor sentiment on that day.

        - Close: This is the last price at which the stock was traded when the market closed for that day. The closing price is commonly used for analysis as it represents the stock’s final value on that trading day.

        - Adj Close (Adjusted Close): This is the closing price adjusted for any actions affecting the stock price, such as dividends, stock splits, or mergers. It’s especially useful for long-term analysis, as it reflects the stock’s value more accurately than the raw closing price.

        - Volume: This represents the total number of shares traded on that specific day. High trading volume usually suggests strong investor interest or significant market events, while low volume could indicate less interest or quieter trading conditions.
   

### 2. **Iris Flower Classification Dataset (Logistic Regression)**:
https://www.kaggle.com/uciml/iris
   - This is a classic dataset that includes 150 samples of iris flowers, each described by four features: `Sepal Length`, `Sepal Width`, `Petal Length`, and `Petal Width`.
   - Each sample is categorized into one of three Iris-species: **Setosa**, **Versicolor**, or **Virginica**.
     
## Project Objectives

The objectives of this project are as follows:

1. **Linear Regression Analysis**:
   - Determine the relationship between two quantitative variables(dependent and independent)
   - Interpret the coefficients and predictive power of the Linear Regression model that will be used on predicting future stock market price.
   - Apply Linear Regression analysis in predicticting future stock market prices on the next five days based on the dependent and independent variables of the of Apple Inc. historical price data (e.g., open, close, high, low, and volume). By using `Close` as independent variable(y) and `Open`, `High`, `Low`,`Volume` as dependent variables(X) and implementing a linear regression, this can obtain predictions for future stock prices of Apple Inc. on a certain amount of span given. 
   - Evaluate model performance using appropriate regression metrics like **Mean Squared Error (MSE)** and **R-squared (R²)**.

2. **Logistic Regression Analysis**:
   - Classify iris flowers into one of the three species using their physical characteristics (sepal length, sepal width, petal length, petal width).
   - Assess the performance of the classification model using metrics such as **Accuracy**, **Precision**, **Recall**, and **F1 Score**.

By the end of this project, we aim to demonstrate the effectiveness of both linear and logistic regression in real-world scenarios, from predicting stock prices to classifying biological species.

## Documentation
### Methodology


