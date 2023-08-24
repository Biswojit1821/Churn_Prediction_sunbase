# Churn_Prediction_sunbase
 Project Report: Customer Churn Prediction

 Project Overview:-
This project, titled "Customer Churn Prediction," is part of the Machine Learning Intern Assessment Assignment at Sunbase. The primary goal is to develop a machine learning model that predicts customer churn based on historical customer data. The project follows a standard machine learning pipeline, including data preprocessing, feature engineering, model building, optimization, and deployment.
Data Description:-
The dataset provided for this project contains historical customer information in CSV format. It includes various customer attributes, interactions, and a binary indicator of whether a customer churned or not.
Data Preprocessing:-
In the data preprocessing phase, the following steps were performed:
- Initial data exploration to understand the dataset's structure.
- Handling of missing data, resulting in no missing values.
- Removal of outliers to ensure data quality and consistency.
- Encoding of categorical variables to prepare them for model training.
- Splitting the dataset into training and testing sets.
 Feature Engineering:-
Several new features were engineered from the dataset to potentially enhance model performance:
- Usage_Per_Bill : The ratio of total usage to monthly bill.
- High_Usage : A binary flag indicating high usage compared to the median.
- Age_Location : Combination of age and location for potential insights.
-  Usage_Per_Month : The ratio of total usage to subscription length.
- Age_Group : Categorization of customers based on age ranges.
- Location_Encoded : Target encoding of the categorical feature 'Location'.
 
Model Selection and Architecture:-
For this project, a neural network was chosen as the machine learning algorithm. The neural network architecture includes several dense layers with different activation functions. The chosen architecture aims to capture complex relationships in the data for accurate predictions.
Model Evaluation:-
The model's performance was evaluated using various metrics:
- Validation accuracy: 0.49955
- Accuracy: 0.49955
- Precision: 0.49745
- Recall: 0.86655
- F1-Score: 0.63206
- Confusion Matrix: [[1394, 8685], [1324, 8597]]
Model Optimization:-
Hyperparameter tuning was performed to optimize the model's predictive performance. The best parameters were identified, and cross-validation scores were calculated to ensure stability and generalization.
Model Deployment:-
The final model is planned to be deployed in a production-like environment, simulating model deployment for real-world use. The model will be capable of receiving new customer data and providing churn predictions.
Conclusion:-
The "Customer Churn Prediction" project successfully developed and evaluated a machine learning model to predict customer churn based on historical customer data. By following a systematic approach, including data preprocessing, feature engineering, model building, optimization, and deployment considerations, the project aims to provide insights into customer churn behavior and enhance customer retention strategies. Further improvements and real-world deployment are potential future steps for this project.

					**Thank You**
