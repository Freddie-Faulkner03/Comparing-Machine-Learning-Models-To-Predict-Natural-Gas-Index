# Comparing Machine Learning Models To Predict The Natural Gas Index
## Overview
This project explores the application of machine learning models to financial market data. Using historical bid and ask prices, the notebook processes raw price information, converts it into meaningful time-series features, and evaluates several neural network architectures for predicting future price movements.

The work includes transforming high-frequency financial data into structured formats such as price deltas and candlestick representations. These engineered features are then used to train and compare different machine learning models. The project examines how each model interprets market patterns and how their performance differs when applied to financial forecasting tasks.

The models implemented include:

• Convolutional Neural Network (CNN) – captures short-term spatial patterns in price windows.

• Multi-Layer Perceptron (MLP) – serves as a baseline fully connected architecture.

• Gated Recurrent Unit (GRU) – learns sequential and temporal relationships within the price data.

The project provides an overall comparison of these architectures and highlights how each performs when predicting market behavior from real-world financial time-series data.

## Technologies Used

• Python

• Pandas & NumPy for data handling and computation

• Matplotlib / Plotly for visualization and candlestick representation

• TensorFlow / Keras for building and training machine learning models

• Scikit-learn for preprocessing and evaluation utilities

• Jupyter Notebook for analysis and experimentation

