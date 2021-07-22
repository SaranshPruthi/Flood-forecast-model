# Flood-forecast-model
This project aims at predicting floods by labeling its danger level after taking in water level and rainfall amount forecasts (models to forecasts water level and rainfall have also been made and presented in this repository) as input and predict the flood danger levels.

Amount of rainfall and water level of the concerned water body are the two major contributors/factors of flood and hence these two had to be necessarily incorporated while making a flood prediction model. Because of the season changes, daily weather variations and human activities in water bodies and surrounding areas, the abrupt rise in water level leading to floods is quite unpredictable and hence an extensive study of past data (rainfall & water level) along with flood trends had to be studied to give forecasts. 

The first step towards developing this model was to make water level and rainfall forecast systems. There are various ML algorithms/classifiers use to forecast data using the analysis on past data. Since the daily river point water level data and rainfall data were in the form of time-series, the best way to approach this model was by exploring and implementing the various univariate and multivariate time-series models. One such effective model is the ARIMA model which has been used in this project.

After the development and optimization of these two forecast models using ARIMA, they were integrated and developed to make the final flood prediction model. Linear Regression and K-Nearest Neighbors (KNN) were the two algorithms/classifiers that were used to develop the flood prediction system using the forecast models.

The flood prediction system developed takes river water level (in metres) and rainfall amount (in millimetres) forecasts as input to the linear regression and KNN classifiers where these forecasts are further modelled in linear regression to foresee the water level rise/fall due to rainfall and uses KNN classifier to classify the flood forecasts into 4 categories namely; No risk, moderate risk, high risk-high flood chances and very high risk of floods.

In this report, data collection process was accomplished by compiling real time data from various government portals like India Water Resources Information System. The data was then cleaned and pre-processed to remove null and invalid values. The water level and rainfall data used in this report is of three consecutive years dating from 1st July, 2018 to 1st July, 2021 of Muri River Point of Puruliya District in West Bengal (Longitude – 85.87; Latitude – 23.36)

