# Change-Point-Detection-Using-LSTM

This project is aimed at detecting changes or anomalies in time series data of solar current using the Long Short-Term Memory (LSTM) model.

## Background

The need for renewable energy sources has led to the rapid development of solar energy technologies, which has resulted in the increase in solar energy production. Time series data from solar panels is an important source of information for monitoring and optimizing solar energy production. However, solar energy production is susceptible to changes due to weather conditions, faulty equipment, or other factors, which may lead to a decline in energy production or even equipment failure. Change point detection is, therefore, important for detecting such changes and taking appropriate action.

## Data

The data used in this project is the solar current time series data obtained from solar panels. The dataset contains information on the solar current produced by the panels at different times. The data is in the form of a time series with multiple variables, such as temperature, humidity, and wind speed.

## Methodology

The LSTM model is a type of recurrent neural network (RNN) that is well-suited for handling time series data. The LSTM model is able to capture long-term dependencies in the data and has been shown to be effective in detecting change points in time series data.

The methodology for this project involves the following steps:

1. Data preprocessing: The time series data is preprocessed to remove any missing values, outliers, and to standardize the data.

2. LSTM model training: The LSTM model is trained on the preprocessed data using a sliding window approach. The model is trained to predict the next value in the time series, given the previous values.

3. Change point detection: Change points are detected by comparing the predicted values with the actual values. A change point is detected when the difference between the predicted value and the actual value exceeds a certain threshold.

## Results

The results of this project show that the LSTM model is effective in detecting change points in time series data of solar current. The model was able to detect changes due to weather conditions and equipment failure. The model was also able to predict the future values of the solar current with high accuracy.

## Conclusion

In conclusion, this project demonstrates the effectiveness of the LSTM model in detecting change points in time series data of solar current. The model can be used for real-time monitoring of solar energy production and for predicting future values of the solar current. The project provides a valuable tool for optimizing solar energy production and reducing the risk of equipment failure.

## Future Work

Future work for this project includes improving the accuracy of the LSTM model and exploring other deep learning models for change point detection. The project can also be extended to include other variables such as temperature, humidity, and wind speed for more accurate change point detection.
