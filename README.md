# Stock-Price-Direction-Prediction-Using-Gaussian-Naive-Bayes
Gaussian Naive Bayes predicts AU Small Finance Bank stock direction (Up/Down) using technical indicators from au-bank.csv. Features engineered include returns, volatility, RSI, MACD. Model achieves 92% accuracy. Risk model labels predictions as Low, Medium, High Risk. Visualizes confusion matrix, risk distribution.

# About

The project uses a dataset (au-bank.csv) containing daily stock prices and trading data for AU Small Finance Bank. Feature engineering creates technical indicators such as daily returns, volatility, moving averages, RSI, MACD, and volume-based metrics. The Gaussian Naive Bayes model is trained to predict whether the stock price will close higher than the previous day (direction = 1 for Up, 0 for Down). The model is evaluated using accuracy, precision, recall, and F1-score, with a confusion matrix visualization. A risk model categorizes predictions based on probability thresholds: Low Risk (≥0.80), Medium Risk (0.60–0.79), and High Risk (<0.60). The risk distribution is visualized, and the top 10 high-confidence (Low Risk) predictions are displayed.
