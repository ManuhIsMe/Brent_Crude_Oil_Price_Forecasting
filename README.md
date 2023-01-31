# Brent_Crude_Oil_Price_Forecasting
The purpose of this project is to develop a machine learning model that can accurately forecast the  Brent crude oil prices using Xgboost. 
Forecasting Historical Brent Crude Oil Prices using Xgboost

Introduction:
The purpose of this project is to develop a machine learning model that can accurately forecast the historical Brent crude oil prices using Xgboost. Brent crude oil is a benchmark used to price two-thirds of the world's oil, including oils exported from the North Sea, Europe and West Africa. Understanding and accurately forecasting the price of Brent crude oil is crucial for oil-producing countries and organizations in the oil industry.

Data:
The dataset used for this project consists of daily Brent crude oil prices from 2000-01-04 to 2022-09-02. The data includes the date, open price, high price, low price, close price, volume, and currency. The data was collected from a reliable source and does not contain any missing or irrelevant values.

Methods:
The following methods were used to develop the forecasting model:

Data preprocessing: The data was preprocessed to convert the date column to the datetime format, set it as the index of the dataframe, and drop the currency column, as it is not relevant to the analysis.

Train-Test split: The data was split into a training set and a testing set. The training set was used to train the model, and the testing set was used to evaluate its performance.

Model training: Xgboost was used to train the model using the training set. The model was optimized using grid search to find the best hyperparameters.

Model evaluation: The model's performance was evaluated using the Mean Squared Error (MSE) metric. The MSE was calculated for the training set and the testing set, and the results were compared.

Model prediction: The trained model was used to make predictions on the testing set. The predicted values were compared to the actual values to evaluate the model's performance.

Results:
The Xgboost model was able to accurately forecast the Brent crude oil prices with a low MSE score. The model performed well on the testing set, with a MSE score that was similar to that of the training set, indicating that the model is not overfitting. The predicted values were in line with the actual values, demonstrating that the model is a good fit for the data.

Conclusion:
In conclusion, Xgboost was able to produce a well-performing model for forecasting historical Brent crude oil prices. The model was able to accurately forecast the prices with a low MSE score, and its performance was consistent on both the training and testing sets. This project provides a valuable tool for organizations in the oil industry to better understand and predict the prices of Brent crude oil, which is a critical benchmark used to price a significant portion of the world's oil.
