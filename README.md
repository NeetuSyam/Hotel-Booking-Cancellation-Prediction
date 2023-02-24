# Hotel-Booking-Cancellation-Prediction
This is a machine learning project to predict the cancellation of hotel bookings using several classification algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Random Forest Classifier, Ada Boost Classifier, Gradient Boosting Classifier, XGBoost, Cat Boost, Extra Trees Classifier, LGBM, Voting Classifier and Artificial Neural Network (ANN). The dataset used for this project is publicly available on kaggle.

Problem Statement
The hotel industry has a problem with cancellations, which can cause a loss of revenue and uncertainty in their operations. To avoid these negative impacts, it is crucial to predict the likelihood of a booking being cancelled. In this project, we will develop machine learning models to predict the cancellation of hotel bookings based on several features such as the lead time, number of adults and children, room type,etc,.

Machine Learning Models
We developed several machine learning models to predict hotel booking cancellations. These models are:
Logistic Regression
K-Nearest Neighbors (KNN)
Random Forest Classifier
Ada Boost Classifier
Gradient Boosting Classifier
XGBoost
Cat Boost
Extra Trees Classifier
LGBM
Voting Classifier
Artificial Neural Network (ANN)

Conclusion
 In comparison to previous models, the CatBoost model initially offered a better F1 score of 99.5%. As a result, here Optuna is choosed to use to implement hyperparameter adjustment for the CatBoost model. A software framework called Optuna is used to automate the optimization of these hyperparameters. Through trial and error, it automatically identifies the ideal hyperparameter settings for great performance. Consequently, the CatBoost model gave an F1 score of 100 percent. For practical usage we deployed our model using an EC2 instance  so users (hotel managers and staff) can interact with the model by providing parameters to check if the customer's probability of cancellation is high or low. 

