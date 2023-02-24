# Hotel-Booking-Cancellation-Prediction
**Libraries used Packages used:** *TensorFlow, Pandas, Numpy, Scikit- Learn*

This is a machine learning project to predict the cancellation of hotel bookings using several classification algorithms such as **Logistic Regression, K-Nearest Neighbors (KNN), Random Forest Classifier, Ada Boost Classifier, Gradient Boosting Classifier, XGBoost, Cat Boost, Extra Trees Classifier, LGBM, Voting Classifier and Artificial Neural Network (ANN)**. The dataset used for this project is publicly available on [kaggle] (https://www.kaggle.com/datasets/vinayakashastri/hotel-booking-cancellation-dataset).

## Problem Statement
Hotel cancellations can be done via their hotel website, app, or by giving them a call. Hotels use strict cancellation policies and overbooking techniques to 
lessen the impact of cancellations, however these strategies can have a detrimental effect on income and the hotel's reputation. A machine learning-based system prototype was created to lessen this impact. Machine learning models can learn about the new patterns and predict hotel booking cancellations. Classification models are trained using data from the hotel's property management system on a day-to-day basis to determine which reservations are "likely to cancel" 
and as a result, to determine net demand.



## Conclusion
 In comparison to previous models, the CatBoost model initially offered a better F1 score of 99.5%. As a result, here Optuna is choosed to use to implement hyperparameter adjustment for the CatBoost model. A software framework called Optuna is used to automate the optimization of these hyperparameters. Through trial and error, it automatically identifies the ideal hyperparameter settings for great performance. Consequently, the CatBoost model gave an F1 score of 100 percent. For practical usage we deployed our model using an EC2 instance  so users (hotel managers and staff) can interact with the model by providing parameters to check if the customer's probability of cancellation is high or low. 

### The results obtained are mentioned below
![alt text]([https](https://github.com/NeetuSyam/Hotel Booking Cancellation Prediction/blob/HotelImages/Hotel4.jpg?raw=true))
