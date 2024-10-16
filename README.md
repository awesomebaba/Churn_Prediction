# Customer Churn Prediction Using Artificial Neural Network (ANN) with TensorFlow/Keras

This project focuses on predicting customer churn using an **Artificial Neural Network (ANN)** model built with **TensorFlow/Keras**. Customer churn refers to the tendency of customers to stop using a company's services. By leveraging the provided features, the ANN model predicts whether a customer is likely to churn or not.

## Features

The model uses the following features to predict customer churn:

1. **gender**: Gender of the customer (encoded as an integer).
2. **SeniorCitizen**: Whether the customer is a senior citizen (0: No, 1: Yes).
3. **Partner**: Whether the customer has a partner (0: No, 1: Yes).
4. **Dependents**: Whether the customer has dependents (0: No, 1: Yes).
5. **tenure**: Number of months the customer has been with the company.
6. **PhoneService**: Whether the customer has a phone service (0: No, 1: Yes).
7. **MultipleLines**: Whether the customer has multiple lines (0: No, 1: Yes).
8. **OnlineSecurity**: Whether the customer has online security service (0: No, 1: Yes).
9. **OnlineBackup**: Whether the customer has online backup service (0: No, 1: Yes).
10. **DeviceProtection**: Whether the customer has device protection service (0: No, 1: Yes).
11. **TechSupport**: Whether the customer has technical support service (0: No, 1: Yes).
12. **StreamingTV**: Whether the customer has streaming TV service (0: No, 1: Yes).
13. **StreamingMovies**: Whether the customer has streaming movies service (0: No, 1: Yes).
14. **PaperlessBilling**: Whether the customer has opted for paperless billing (0: No, 1: Yes).
15. **MonthlyCharges**: The monthly charge for the customer's account (float).
16. **TotalCharges**: The total charge for the customer's account (float).
17. **Churn**: The target variable indicating churn (0: No churn, 1: Churn).
18. **InternetService_DSL**: Whether the customer uses DSL internet (True/False).
19. **InternetService_Fiber optic**: Whether the customer uses Fiber optic internet (True/False).
20. **InternetService_No**: Whether the customer has no internet service (True/False).
21. **Contract_Month-to-month**: Whether the customer has a month-to-month contract (True/False).
22. **Contract_One year**: Whether the customer has a one-year contract (True/False).
23. **Contract_Two year**: Whether the customer has a two-year contract (True/False).
24. **PaymentMethod_Bank transfer (automatic)**: Whether the customer uses bank transfer for automatic payments (True/False).
25. **PaymentMethod_Credit card (automatic)**: Whether the customer uses credit card for automatic payments (True/False).
26. **PaymentMethod_Electronic check**: Whether the customer uses electronic check for payments (True/False).
27. **PaymentMethod_Mailed check**: Whether the customer uses mailed check for payments (True/False).

## Technical Details

### Model: **Artificial Neural Network (ANN)**

The ANN model is designed to capture complex patterns in the dataset using multiple hidden layers. It consists of the following components:
- **Input Layer**: Takes in the customer feature data.
- **Hidden Layers**: One or more fully connected layers with activation functions like **ReLU**.
- **Output Layer**: A single neuron with a **sigmoid** activation function to predict churn probability (0 or 1).

## Data Preprocessing

- **Feature Scaling**: Numeric features like `MonthlyCharges` and `TotalCharges` are scaled for the ANN using **Min-Max scaling** or **Standardization**.
- **Categorical Encoding**: Categorical variables such as `InternetService`, `Contract`, and `PaymentMethod` are converted into binary indicators (one-hot encoding) for better model performance.
## Conclusion

This project uses a simple yet effective ANN model to predict customer churn based on a variety of customer-related features. The results can be used by companies to identify customers at risk of churning and implement targeted strategies to retain them.

