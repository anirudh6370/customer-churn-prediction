# Customer Churn Prediction

## Overview
Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. Predicting customer churn is crucial for businesses as it helps them identify at-risk customers and take proactive measures to retain them. In this project, we aimed to predict customer churn using machine learning techniques.

## Dataset
We utilized the Telco Customer Churn dataset available on Kaggle, which contains information about customers' demographics, services subscribed to, and churn status. The dataset consists of 7021 entries and 20 features.

## Data Preprocessing
- Checked for missing values: Fortunately, there were no missing values in the dataset.
- Removed duplicate records: 22 duplicate records were identified and removed.
- Data type conversion: Converted the 'TotalCharges' column from object type to float64.
- Handling categorical variables: Replaced 'No internet service' with 'No' and 'No phone service' with 'No'.
- One-hot encoding: Applied one-hot encoding to categorical variables such as 'InternetService', 'Contract', and 'PaymentMethod'.

## Exploratory Data Analysis (EDA)
- Analyzed the distribution of each attribute and its relationship with churn.
- Visualized categorical variables using count plots to understand their impact on churn.

## Model Creation
- Split the dataset into training and testing sets with a 80-20 ratio.
- Built a Sequential neural network using TensorFlow and Keras.
- Trained the model with 100 epochs and evaluated its performance using binary cross-entropy loss and accuracy metrics.

## Results
- Achieved an accuracy of approximately 82% on the test set.
- Identified key factors influencing customer churn, such as contract type, monthly charges, and tenure.
- Demonstrated the effectiveness of machine learning in predicting customer churn, enabling businesses to take proactive measures to retain customers.

## Conclusion
Customer churn prediction is a critical task for businesses to maintain customer satisfaction and loyalty. By leveraging machine learning techniques, businesses can identify potential churners early and implement targeted strategies to mitigate churn. This project demonstrates the application of machine learning in customer churn prediction and highlights the importance of data-driven decision-making in customer relationship management.

