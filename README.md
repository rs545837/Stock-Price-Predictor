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
- Linear Refression: Prone to overfitting and too simple
- MLP: Additional layers will improve pattern recognition
- Simple RNN: Prone to vanishing gradient problem. Will still perform acceptably as stock prices are drive by current trends.
- LSTM RNN: Overcoming the vanishing gradient problem will further improve performance and consider long term trends
- GRU: Improves on LSTM with better accuracy and training efficiency
- Prophet: Specially designed by Facebook to Predict future values and thus should have the best performance
