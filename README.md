### Predicting Airline Ticket Pricing

**Vikash Sinha**

#### Executive summary
This project aims to develop a predictive model for airline ticket pricing. By leveraging regression models, including Linear Regression, Decision Trees, and Random Forest, we can predict optimal ticket prices. The project also provides insights into the best times to buy tickets and identifies patterns in airline pricing trends.

#### Rationale
Airline ticket prices fluctuate due to several factors such as demand, time of booking, seasonality, and competition. Being able to predict these fluctuations can help both consumers and airline companies make informed decisions, such as the best time to purchase tickets or adjust pricing strategies to remain competitive.

#### Research Question
Can we build a model to accurately predict airline ticket prices and identify the best time to purchase tickets for cost savings?

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

Additionally, time series forecasting using ARIMA (AutoRegressive Integrated Moving Average) is planned conducted to predict future prices based on historical trends.

#### Results
The Random Forest model provided the most accurate predictions for airline ticket prices, with a well-tuned set of hyperparameters identified through GridSearchCV. The ARIMA model also identified clear seasonality in ticket pricing, indicating optimal purchase windows for travelers.

#### Next steps
The project can be extended in the following ways:

Integrate additional features such as holiday seasons, special events, and competitor pricing to enhance prediction accuracy.
Implement real-time scraping and prediction to provide users with up-to-date recommendations on the best time to purchase airline tickets.
Explore deep learning techniques such as LSTM for time series forecasting.

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
For any questions or further information about this project, please contact vikash.sinha@gmail.com