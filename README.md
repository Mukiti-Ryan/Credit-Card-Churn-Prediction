# Credit-Card-Churn-Prediction
Credit Card Churn Prediction Models. There are two prediction models in this repository.

# Credit-Card-Churn-Prediction (RC, RFC, GSCV)

The First One is trained using the following models:

1. RidgeClassifier
2. RandomForestClassifier
3. GridSearchCV

A Machine Learning Model Trained to Predict Churning Among Customers of an Internet Service.

The model has the following accuracies with various models used to train and test the model:

|                       |RidgeClassifier  |RandomForestClassfier |GridSearchCV |     
|-----------------------|-----------------|----------------------|-------------|
| Training Set Accuracy |     84.67%      |        98.39%        |     N/A     |
| Testing Set Accuracy  |     83.79%      |        97.38%        |     N/A     |
| Overall Accuracy      |     84.23%      |        97.89%        |    90.46%   |

GridSearchCV is used for hyperparameter tuning in machine learning models. It exhaustively searches over a specified set of hyperparameters and finds the combination that gives the best performance for a given performance metric. This helps in optimizing the model's performance and making it more accurate.

# Credit-Card-Churn-Prediction (TFDF)

The Second One is trained using TensorFlow Decision Forests(TFDF). The Overall accuracy using this model is 92.20%
