
Overview
This project is aimed at predicting sales for different products at various stores of the Favorita chain in Ecuador. The data provided includes information on store location, product type, dates, and past sales.

Requirements
Python 3.7+
pandas
scikit-learn
Data
The data for this project was provided by the Favorita chain and can be found in the data directory. The data consists of the following files:

train.csv: the training set containing historical sales data
test.csv: the test set containing information on store location, product type, and dates for which sales predictions are to be made
stores.csv: information on store location and type
items.csv: information on product types
Feature Engineering
To improve the performance of our model, we performed feature engineering on the data. We extracted the following features from the date column: year, month, day, day of week, and week of year.

Model Building
We used a Random Forest Regressor to build our sales prediction model. The model was trained on the training set using the extracted features and past sales data. We then evaluated the model on the test set using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Squared Log Error (MSLE), and Root Mean Squared Log Error (RMSLE) metrics.

Results
Our Random Forest model performed reasonably well with an MSE of 44.52, RMSE of 6.67, MSLE of 0.117, and RMSLE of 0.342.

Usage
To use this model to make sales predictions on new data, you can run the predict.py script. This script takes the path to a CSV file containing data on store location, product type, and dates as input, and outputs a CSV file containing the predicted sales for each row in the input file.

Conclusion
This project demonstrates how machine learning can be used to predict sales for a retail chain using historical sales data and other relevant features. The Random Forest Regressor model we built was able to make accurate predictions on the test set, indicating its potential usefulness for sales forecasting in the retail industry.









# Authors

Richmond E.Y Abake
