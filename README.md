# Temperature Prediction Using LSTM

## Overview
This project focuses on predicting weather temperatures using Long Short-Term Memory (LSTM) neural networks. The model is trained to forecast future temperatures based on historical minimum and maximum temperature data.

## Data Source
The dataset used in this project comes from the **Global Historical Climatology Network (GHCN) - Daily**. GHCN-Daily is a comprehensive database that compiles historical daily temperature, precipitation, and snow records from multiple sources worldwide. It includes over 100,000 stations and provides data on more than 40 meteorological elements, including daily maximum and minimum temperatures, precipitation, snowfall, and snow depth. The dataset is well-suited for climate monitoring and research, making it an excellent choice for weather prediction models.

## Purpose
The project was created as a learning exercise to improve my skills in:
- Machine Learning (ML)
- Neural Networks
- LSTM models

## What is LSTM?
Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) designed to handle sequential data, such as time series. Unlike traditional RNNs, LSTMs can learn long-term dependencies and remember important patterns over time, making them well-suited for weather prediction.

## How It Works
1. The model takes historical temperature data as input.
2. It processes the sequence using LSTM layers to capture patterns and trends.
3. The output is a forecast of future temperature values based on past observations.

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy, Pandas
- Matplotlib, Seaborn (for data visualization)

## Future Improvements
- Experimenting with additional weather variables
- Fine-tuning hyperparameters for better accuracy
- Comparing results with other ML models

## Author
This project was developed as part of my learning journey in machine learning and deep learning.
