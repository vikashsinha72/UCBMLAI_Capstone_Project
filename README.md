### Predicting Airline Ticket Pricing

**Vikash Sinha**

#### Executive summary
This project aims to develop a predictive model for airline ticket pricing. By leveraging multiple regression models, including Linear Regression, Decision Trees, and Random Forest, we aim to predict optimal ticket prices. The project may helps to provide insights into the best times to buy tickets and identifies patterns in airline pricing trends, giving both consumers and airlines the ability to make better decisions.

#### Rationale
Airline ticket prices fluctuate due to several factors such as demand, time of booking, seasonality, and competition. Being able to predict these fluctuations can help both consumers and airline companies make informed decisions, such as the best time to purchase tickets or adjust pricing strategies to remain competitive.

#### Research Question
Can we build a model to accurately predict airline ticket prices for future travel dates, considering different airlines, travel times, and seasons?

#### Data Sources
The data used in this project is sourced from Kaggle, specifically:

Airfare ML Predicting Flight Fares Dataset
The dataset contains historical flight fare information collected from the EaseMyTrip website through web scraping. It includes important features such as airline, ticket fare, source, destination, class, and more.

#### Methodology
To answer the research question, we employ multiple regression models including:

Linear Regression
Decision Trees
Random Forests
We preprocess the data, including handling non-numeric values, and apply grid search to tune hyperparameters. The models are evaluated using cross-validation, and the performance is assessed using metrics like RMSE (Root Mean Squared Error), MSE (Mean Squared Error), and R² (R-squared).

Additionally, time series forecasting using ARIMA (AutoRegressive Integrated Moving Average) will be planned to conduct for predicting future prices based on historical trends.

#### Results 
The Random Forest model outperformed the other models in terms of predictive accuracy. The following insights were gathered:

Feature Importance: The "Class" feature had the highest importance in the model, significantly affecting the ticket fare. Other important features included Flight_code and Duration_in_hours.

Correlation Analysis: There was a notable negative correlation between "Class" and fare, suggesting lower fares for higher classes in the dataset (possibly due to encoding).

Cross-Validation: Cross-validation RMSE scores indicated that Random Forest provided the most stable and accurate predictions.

For Random Forest:
Cross-validation MSE: 84,322,403
Test RMSE: 8,977
Test R²: 0.798

#### Next steps
The project can be extended in the following ways:

Additional Features: Incorporating features such as holiday seasons, special events, and competitor pricing could improve model accuracy.
Real-Time Data: Implement real-time data scraping and prediction to provide up-to-date recommendations on the best time to purchase tickets.
Advanced Time Series Models: Explore deep learning models like LSTMs (Long Short-Term Memory networks) for improved time series forecasting.

#### Outline of project

- https://github.com/vikashsinha72/UCBMLAI_Capstone_Project/blob/main/PredictingAirTicketPricing.ipynb
- data: https://github.com/vikashsinha72/UCBMLAI_Capstone_Project/blob/main/Cleaned_dataset.csv



##### Contact and Further Information
For any questions or further information about this project, please contact vikash.sinha@gmail.com