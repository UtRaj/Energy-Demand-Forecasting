# Electricity Consumption Forecasting in Finland using LSTM

This project demonstrates a time series forecasting model for electricity consumption in Finland using LSTM (Long Short-Term Memory) neural network. 

## Overview

The goal of this project is to build and evaluate a model that can accurately predict future electricity consumption based on historical data. The model utilizes LSTM, a type of recurrent neural network well-suited for time series analysis.

## Dataset

The project utilizes an electricity consumption dataset for Finland spanning from 2016 to 2021. The dataset includes hourly electricity consumption data.

## Methodology

The project involves the following steps:

1. **Data Exploration:** Initial analysis of the dataset to understand its structure, distribution, and patterns.
2. **Feature Extraction:** Extraction of relevant features from the dataset, including year, month, and day.
3. **Data Visualization:** Visualizations of electricity consumption trends over time, including yearly, monthly, and hourly breakdowns.
4. **LSTM Model:** Building and training an LSTM model to predict future electricity consumption.
5. **Train, Validation, and Test Dataset:** Splitting the dataset into training, validation, and testing sets.
6. **Model Structure:** Defining the architecture of the LSTM model.
7. **Model Training:** Training the LSTM model using the training dataset and optimizing its performance.
8. **Model Evaluation:** Evaluating the model's performance on the validation and test datasets using metrics like Root Mean Squared Error (RMSE).
9. **Future Forecasting:** Utilizing the trained model to forecast future electricity consumption.
10. **Conclusion:** Summarizing the project's findings and model performance.

## Code Structure

The code is structured as follows:

1. Importing necessary libraries (Pandas, NumPy, Matplotlib, Seaborn, Keras, TensorFlow).
2. Loading the electricity consumption dataset.
3. Data exploration and preprocessing.
4. Feature engineering and data manipulation.
5. Data visualization to understand trends and patterns.
6. Building the LSTM model.
7. Splitting the data into training, validation, and testing sets.
8. Training the LSTM model.
9. Evaluating the model's performance.
10. Forecasting future electricity consumption.
11. Plotting the actual consumption and model predictions.

## Results

The LSTM model demonstrates a reasonable accuracy in predicting electricity consumption, both for training and testing datasets. The visualizations provide a comprehensive understanding of the model's performance over time. The model can be further improved by exploring additional features and techniques.

## Future Work

* Experiment with different model architectures and hyperparameters.
* Incorporate external factors (weather, holidays) to improve prediction accuracy.
* Develop a user interface to allow users to interact with the model and visualize its predictions.

