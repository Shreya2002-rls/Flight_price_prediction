Flight Price Prediction
Problem Statement
Flight ticket prices are often unpredictable, varying drastically from day to day. This project aims to analyze historical flight ticket data and develop a model to predict flight prices. Using data from various airlines between March and June 2019, this project explores factors that impact pricing and builds a machine learning model to make predictions.

Project Structure
Data Collection:

The dataset contains flight information including the airline, date of journey, source and destination, route, departure and arrival times, duration, total stops, and price.
Total rows: 10,683
Columns: 11
Target Variable: Price
Exploratory Data Analysis (EDA):

The dataset is explored to identify trends and insights related to flight prices. This involves data visualization using libraries like Matplotlib and Seaborn.
Key factors affecting prices such as the airline, total stops, and flight duration are analyzed.
Feature Engineering:

Date-time columns like Dep_Time, Arrival_Time, and Date_of_Journey are processed for model training.
Routes and stop details are converted into numeric representations.
Model Building:

Various machine learning algorithms are applied to predict flight prices, including:
Linear Regression
Random Forest
Decision Tree
XGBoost
Model evaluation metrics include RMSE and R-squared to assess prediction accuracy.

Data Visualization:
Price distributions and relationships between variables are visualized to assist in feature selection and data insights.
Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib and Seaborn: For data visualization.
Scikit-learn: For machine learning models and evaluation metrics.
XGBoost: For advanced boosting techniques.

Results
The best-performing model was the XGBoost algorithm, achieving the lowest RMSE and highest R-squared score.
The model can now be used to predict flight prices for new data based on key factors such as airline, total stops, and travel duration.
