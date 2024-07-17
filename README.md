Airline Fare Prediction Using Machine Learning
Objective: Develop a machine learning model to predict airline fares based on various flight details and
relevant factors.
Dataset: Collected from flight information databases, including Flight details airline, departure/arrival
airports, dates, Day of the week, month, direct or layover flights.
Data Pre-processing: This involved handling missing values by imputing them using the median for
numerical features and mode for categorical features. Such as airline, departure and arrival airports
were encoded using one-hot encoding. Numerical features like the day of the week and time to
departure were standardized using Standard Scaler. Additional features were extracted from date
fields. The dataset was split into training and testing sets to ensure robust model evaluation.
Feature Engineering: Created features like time to departure, seasonal trends. Included interaction
terms between features, such as the interaction between airline and departure airport.
Model Selection and Training: Evaluated models Linear Regression, Decision Trees, Random Forest,
Gradient Boosting, K-Nearest Neighbors (KNN). KNN, achieving 82% accuracy in fare prediction.
Technologies Used: Python, Pandas, NumPy, Matplotlib, seaborn, Scikit-learn
