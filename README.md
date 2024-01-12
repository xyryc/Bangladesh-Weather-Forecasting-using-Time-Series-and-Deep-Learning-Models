Exploring Advanced Models for Time Series-Based Weather Forecasting in Bangladesh: A Comparative Analysis of ARIMA, SARIMA, FB-Prophet, LSTM and BiLSTM Models

Dataset Link: https://www.kaggle.com/datasets/anik43/bangladesh-historical-weather-dataset-2008-2023

About Dataset: The dataset was sourced from the Historical Weather API, available
at https://open-meteo.com. This API offers historical weather information, enabling
users to access data related to past weather conditions across different locations. The
primary aim of utilizing the Historical Weather API was to gather data for analyzing
and comprehending historical weather patterns within a specified timeframe and ge-
ographical region. This collected information served as the training dataset for our
models. The API provides various parameters and variables, including time, weather-
code (wmo code), temperature 2m max (°C), temperature 2m min (°C), temperature
2m mean (°C), sunrise (iso8601), sunset (iso8601), precipitation sum (mm), rain sum
(mm), and snowfall sum (cm). The data collection process involved querying the His-
torical Weather API with specific parameters and geographical coordinates to retrieve
historical weather data for the desired time periods. Subsequently, the obtained data
was stored in CSV format and further processed for analysis.

Kaggle Notebooks: 
ARIMA: https://www.kaggle.com/code/anik43/arima-weather-forecasting-bangladesh-mse-3-05
SARIMA: https://www.kaggle.com/code/anik43/sarima-weather-forecasting-bangladesh-mse-19-90
Facebook Prophet: https://www.kaggle.com/code/anik43/prophet-weather-forecasting-bangladesh-mse-2-509
LSTM: https://www.kaggle.com/code/anik43/lstm-weather-forecasting-bangladesh-mse-0-0016
BiLSTM: https://www.kaggle.com/code/anik43/bilstm-weather-forecasting-bangladesh-mse-0-0026

Abstract: This study analyzes the field of advanced models for time series and deep learning-based weather forecasting in Bangladesh by comparing the ARIMA, SARIMA, FB-Prophet, LSTM and  Bi-LSTM models. The study employs deep learning and time series techniques to improve decision-making and resource management, especially in the face of extreme and unpredictable weather events, with the main objective of improving weather forecasting accuracy. Acquiring and analyzing the most recent historical weather dataset that is unique to Bangladesh is an essential part of the research. Predictions of rainfall and temperature are the main focus of the analysis, which shows differences in performance amongst the five models. It is noticeable that the Long Short-Term Memory (LSTM) model performs exceptionally well, with the lowest mean squared error (MSE) for both rainfall and temperature. Although the LSTM model is quite precise, the FB-Prophet model has a more reliable forecasting curve because of its inherent benefits. The adaptability of FB-Prophet is derived from its capacity to catch seasonality and steady, long-term trends with discernible patterns. Though the FB-Prophet model has slightly higher mean square error, it is robust against outliers and sudden variations, which makes it ideal for situations with inconsistent anomalies. This feature adds to its dependability in producing reliable and accurate forecasts even when there are anomalies in the data. The FB-Prophet model performs better than other models in certain weather prediction tasks, such as temperature prediction, demonstrating its ability to capture seasonality and long-term trends. However, the ARIMA model is very effective at predicting rainfall. This thesis reveals insightful details about the relative effectiveness of comprehensive weather forecasting models, providing an in-depth analysis of their benefits and drawbacks. The results show how important it is to choose models according to the particulars of the data and the type of weather variable being studied. In the end, the study lays the foundation for developing weather forecasting and encouraging more accurate forecasts and well-informed decision-making.
