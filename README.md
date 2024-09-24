# Customer Churn Prediction for KKBOX

This project involves developing a machine learning model to predict customer churn for the music streaming service KKBOX. The model leverages transaction data, user logs, and membership data to identify key factors that influence customer churn. The goal of the project is to build a robust model that can accurately predict which users are likely to stop using the service, helping KKBOX improve retention strategies.

## Features

- **Data Sources:** 
  - Transaction data, user logs, and membership data from KKBOX.
- **Feature Engineering:** 
  - Performed feature engineering to extract key insights and trends from user behavior, such as transaction history, streaming habits, and membership details.
- **Churn Prediction Model:** 
  - Applied the LightGBM algorithm for efficient and scalable training.
- **Model Validation:** 
  - Used K-fold cross-validation to ensure robust model performance and generalizability.

## Technologies Used

- **Machine Learning Model:** LightGBM
- **Data Processing:** Pandas, NumPy
- **Model Validation:** K-fold cross-validation
- **Performance Metric:** AUC (Area Under the Curve)
- **Hyperparameter Tuning:** GridSearchCV for optimizing model performance
