# GYM_Churn-prediction-
Gym Churn Prediction
This project aims to predict customer churn in a gym setting using various machine learning algorithms. The dataset contains several features, including demographic information and usage statistics, and the target variable is 'churn', which indicates whether a customer has left the gym

#Dataset Features

The dataset includes the following features:


gender: Customer's gender (e.g., Male, Female)


near_location: Whether the customer is near the gym's location (e.g., Yes, No)


partner: Whether the customer has a gym partner (e.g., Yes, No)


promo_friends: Whether the customer was referred by friends (e.g., Yes, No)


phone: Whether the customer has provided a phone number (e.g., Yes, No)

contract_period: Duration of the customer's contract (in months)

group_visits: Number of group visits by the customer

age: Age of the customer

avg_additional_charges_total: Total additional charges (e.g., for classes, personal training)

month_to_end_contract: Number of months remaining until the contract ends

lifetime: The length of time (in months) the customer has been with the gym

avg_class_frequency_total: Average frequency of class attendance by the customer

avg_class_frequency_current_month: Frequency of class attendance in the current month

churn: Target variable (whether the customer has churned)

#Objective

The objective of this project is to build a predictive model that can identify whether a gym member will churn. We employ different classification algorithms and use hyperparameter tuning to achieve the best model performance.

#Algorithms Used

Logistic Regression

AdaBoost


#Model Performance

Logistic Regression achieved an accuracy of 93.34%, showing a slight difference compared to the other models.
AdaBoost algorithm achived an accuracy of  91.92%


#Conclusion
The project demonstrates that Logistic Regression performs slightly better than AdaBoost for predicting gym churn.
