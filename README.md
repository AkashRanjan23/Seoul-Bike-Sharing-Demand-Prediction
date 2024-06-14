# Seoul-Bike-Sharing-Demand-Prediction (Regression)

![pngwing com (13)](https://github.com/AkashRanjan23/Seoul-Bike-Sharing-Demand-Prediction/assets/150953524/200f8cbb-19db-4441-b0e1-7f9eacdd0524)

**Forecasting Bike Rental Demand for Capital Bikeshare**

Bike sharing systems offer a convenient and automated means of renting bicycles through a network of kiosk locations spread throughout a city. Users can rent a bike from one location and return it to another, making the system highly flexible and suitable for short-term, on-demand use. As of now, there are over 500 bike-sharing programs globally.

These systems generate substantial data, recording details such as the duration of travel, departure location, arrival location, and time elapsed. This extensive data collection transforms bike sharing systems into a sensor network, providing valuable insights for studying urban mobility patterns.

**Project Objective**

The primary goal of this project is to forecast the bike rental demand for the Capital Bikeshare program in Washington, D.C., using historical usage data combined with weather data. Accurately predicting the bike count required at each hour is crucial to ensure a stable supply of rental bikes, thereby reducing waiting times and enhancing mobility comfort for users.

**Project Components**

1. **Data Collection and Preprocessing**: Gather historical bike rental data and relevant weather data. Clean and preprocess the data to ensure it is suitable for analysis.

2. **Exploratory Data Analysis (EDA)**: Perform EDA to understand usage patterns, identify trends, and uncover relationships between bike rentals and various factors such as weather conditions, time of day, and location.

3. **Feature Engineering**: Develop features that capture key aspects of the data, such as weather conditions, time of day, day of the week, and seasonality, to improve the accuracy of the demand forecasts.

4. **Model Development and Training**: Build and train predictive models using machine learning techniques. Evaluate different models to find the best one for forecasting bike rental demand.

5. **Forecasting and Validation**: Use the selected model to forecast bike rental demand. Validate the model's performance using appropriate metrics to ensure its reliability and accuracy.

**Significance**

By accurately forecasting the hourly bike rental demand, this project aims to:
- Enhance the efficiency and user experience of the Capital Bikeshare program.
- Provide a stable supply of rental bikes, minimizing waiting times for users.
- Contribute to better urban mobility planning and management.

This project not only addresses a critical operational need for bike sharing systems but also offers valuable insights into urban mobility patterns, benefiting both the service providers and the city’s residents.

# **Problem Statement**
**Currently, rental bikes are being introduced in many urban cities to enhance mobility comfort and convenience. Ensuring that rental bikes are available and accessible to the public at the right time is crucial, as it reduces waiting times and improves user satisfaction. Consequently, maintaining a stable supply of rental bikes throughout the day becomes a significant concern for city planners and bike-sharing operators. The key challenge lies in accurately predicting the number of bikes needed each hour, taking into account various factors such as historical usage patterns and weather conditions. This prediction is essential for optimizing bike distribution and ensuring a seamless and efficient bike-sharing experience for users.**

The libraries used in the code are:

1. pandas: For data manipulation and analysis.
2. numpy: For numerical computing.
3. matplotlib.pyplot: For creating plots and visualizations.
4. seaborn: For statistical data visualization.
5. calendar: For working with dates and calendars.
6. LabelEncoder: From sklearn.preprocessing, for converting categorical data to numerical data.
7. SelectKBest and f_regression: From sklearn.feature_selection, for feature selection.
8. variance_inflation_factor: From statsmodels.stats.outliers_influence, for feature selection.
9. StandardScaler: From sklearn.preprocessing, for feature scaling.
10. PCA: From sklearn.decomposition, for dimensionality reduction.
11. train_test_split: From sklearn.model_selection, for splitting the data into training and testing sets.
12. GridSearchCV and RandomizedSearchCV: From sklearn.model_selection, for hyperparameter tuning.
13. LinearRegression, RandomForestRegressor, and SVR: From sklearn.linear_model and sklearn.ensemble, for regression modeling.
14. mean_absolute_error, mean_squared_error, r2_score: From sklearn.metrics, for evaluation metrics.
15. cross_val_score: From sklearn.model_selection, for cross-validation.

These libraries are commonly used in data preprocessing, feature selection, modeling, and evaluation in machine learning projects.
