# Financial time-series data forecasting Using CNN and LSTM

## Overview
This project utilizes Python libraries such as TensorFlow and pandas to predict the opening price of Apple Inc. (AAPL) stock using a deep learning approach. The model employs Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) algorithms, leveraging historical stock data from 2014 to 2024.

## Dataset
The dataset consists of historical stock prices for AAPL from 2014 to 2024, which includes various features such as:
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume

## Data Preprocessing
To ensure the model's effectiveness, the dataset undergoes the following preprocessing steps:
1. **Data Normalization**: The min-max scaler is used to normalize the data, scaling the values to a range between 0 and 1. This helps in speeding up the convergence of the model.

## Model Architecture
The model is built using a combination of CNN and LSTM layers, which allows it to capture both spatial and temporal features in the data. The architecture includes:
- Convolutional layers for feature extraction
- LSTM layers for capturing time dependencies

## Requirements
To run this project, you will need the following Python packages:
- TensorFlow
- pandas
- NumPy
- Matplotlib (optional for visualizations)

## Output shortcut
![CNN fitting result](https://github.com/user-attachments/assets/981e8c66-7b66-4cd4-8529-91f9416f7064)
