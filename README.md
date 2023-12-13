Overview


Welcome to the second contest of AImprove! In this competition, participants will tackle the task of cleaning and preprocessing a given dataset to build an accurate regression model. The dataset contains various 

features, some of which may have missing values, outliers, or inconsistencies that need to be addressed before building the model. Participants are expected to employ effective data preprocessing techniques to 

clean, transform, and prepare the data for regression analysis.


Description


The primary objective of this competition is to develop a regression model that accurately predicts a target variable based on the cleaned dataset. The model's performance will be evaluated based on the mean square 

error (MSE), where lower values indicate better predictive accuracy.

Evaluation


The performance of the models will be assessed using the mean square error (MSE) on a held-out validation set. Participants should aim to minimize the MSE to improve the predictive quality of their regression 

models.


Dataset Description


Name: Precipitation Data

Description:


This dataset captures various meteorological parameters recorded on a daily basis. It includes information about temperature, dew point, humidity, air pressure, visibility, wind speed, precipitation, and events.

Columns:

Date: The date of the recorded data.


TempHighF: Highest temperature in Fahrenheit for the day.


TempAvgF: Average temperature in Fahrenheit for the day.


TempLowF: Lowest temperature in Fahrenheit for the day.


DewPointHighF: Highest dew point in Fahrenheit for the day.


DewPointAvgF: Average dew point in Fahrenheit for the day.


DewPointLowF: Lowest dew point in Fahrenheit for the day.


HumidityHighPercent: Highest percentage of humidity for the day.


HumidityAvgPercent: Average percentage of humidity for the day.


HumidityLowPercent: Lowest percentage of humidity for the day.


SeaLevelPressureHighInches: Highest sea level pressure in inches for the day.


SeaLevelPressureAvgInches: Average sea level pressure in inches for the day.


SeaLevelPressureLowInches: Lowest sea level pressure in inches for the day.


VisibilityHighMiles: Maximum visibility in miles for the day.


VisibilityAvgMiles: Average visibility in miles for the day.


VisibilityLowMiles: Minimum visibility in miles for the day.


WindHighMPH: Highest wind speed in MPH for the day.


WindAvgMPH: Average wind speed in MPH for the day.


WindGustMPH: Maximum wind gust in MPH for the day.


PrecipitationSumInches: Total precipitation in inches for the day (target variable).


Events: Any significant weather events that occurred during the day (e.g., rain, thunderstorm).


Target Variable to Predict: PrecipitationSumInches


Missing or null values may be present in the dataset. Preprocessing might be necessary before performing analysis or building predictive models.

