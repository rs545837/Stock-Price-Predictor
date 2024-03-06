# Stock-Price-Predictor

The purpose of this project is to compare the performance of different machine learning apporaches used to predict future sotck prices.

## Factors Compared Include:
- Time/Computational resources to train.
- Model Accuracy
- How well the model genralizes to various different stocks.


## Models Used
The following models will be trained and compared:
- Linear Regression
- Multilayer Perceptron (MLP)
- Simple Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM RNN)
- Gated Recurrent Unit (GRU)
- Facebook Prophet

## Dataset Collection
Yahoo Finance data was collected using the yfinance Python modeule for complete historical and current data of many stocks.

## Model Hypotheses
The explaination of my predictions are as follows:
- Linear Regression: Prone to overfitting and too simple
- MLP: Additional layers will improve pattern recognition
- Simple RNN: Prone to vanishing gradient problem. Will still perform acceptably as stock prices are drive by current trends.
- LSTM RNN: Overcoming the vanishing gradient problem will further improve performance and consider long term trends
- GRU: Improves on LSTM with better accuracy and training efficiency
- Prophet: Specially designed by Facebook to Predict future values and thus should have the best performance

## Stock Prediction Hypothesis
Based on the historical data of major stocks such as Amazon, Apple and Google, I predict most stocks will have an upwards trajectory and comparable yearly trends. For example, Amazon's one year stock history has an increase during the summer months and December holiday season.

> **_NOTE1:_**  I believe my standard models will generalize to stocks that historically follow these common or predictable patterns, but not as well to less predictable stocks.

> **_NOTE2:_** I believe the prophet model weill best generalize to even historically unpredictable stocks due to its complexity, Prophet is a pre-trained model already designed to handle a variety of stocks.
