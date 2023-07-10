# Stock Prices Prediction Project

This project focuses on predicting future stock prices using machine learning techniques. The goal is to provide accurate predictions to investors, enabling them to maximize returns and make informed decisions on buying and selling securities.

## Project Overview

In this project, I trained two models, a Ridge linear regression model and a deep neural network model, to predict future stock prices. The models were trained using historical stock price data and transaction volume. The deep neural network model utilized the Long Short Term Memory (LSTM) architecture, which is well-suited for sequence prediction tasks.

Python programming language was used for the implementation, along with several libraries including:

- Pandas: Used for data manipulation and analysis.
- Numpy: Employed for numerical computations and array operations.
- Plotly: Utilized for interactive and visually appealing data visualization.
- Scipy: Used for scientific computing and statistical analysis.
- Matplotlib: Employed for creating various plots and visualizations.
- Scikit Learn: Utilized for machine learning algorithms and evaluation metrics.
- Keras from TensorFlow: Used for implementing the LSTM deep neural network model.

## Dataset

The dataset used in this project consists of historical stock price data along with transaction volume. The data was divided into two sets: 75% for training the models and 25% for testing the models performance.

## Project Workflow

The project followed the following workflow:

1. Data preprocessing: The dataset was cleaned and transformed to ensure compatibility with the models. This involved handling missing values, normalizing the data, and splitting it into training and testing sets.

2. Model training: Both the Ridge linear regression model and the LSTM deep neural network model were trained using the training dataset.

3. Model evaluation: The trained models were evaluated using the testing dataset. Evaluation metrics such as mean squared error (MSE), and accuracy score were calculated to assess the models' performance.

4. Prediction visualization: The predicted stock prices were visualized using Plotly and Matplotlib to provide insights and facilitate interpretation of the results.

## Conclusion

The stock price prediction project successfully trained and evaluated two models, the Ridge linear regression model and the LSTM deep neural network model. By accurately predicting future stock prices, investors can make informed decisions on buying and selling securities, maximizing their returns. Python and various libraries such as Pandas, Numpy, Plotly, Scipy, Matplotlib, Scikit Learn, and Keras from TensorFlow were used in the implementation.

Future improvements to the project could involve exploring additional models, refining data preprocessing techniques, and conducting further analysis on the predicted stock prices to identify potential investment opportunities.
