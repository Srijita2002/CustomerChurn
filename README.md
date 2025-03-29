# Customer Churn Prediction

## Overview

Customer churn prediction is a critical task for businesses aiming to retain their customers. This project applies machine learning techniques to predict customer churn using various classification models.

Technologies Used

Programming Language: Python

Libraries:

numpy - Numerical computing

pandas - Data manipulation

matplotlib, seaborn - Data visualization

sklearn - Machine learning utilities

imblearn - Handling imbalanced datasets (SMOTE)

xgboost - Gradient boosting algorithm

Dataset

The dataset contains customer details, service usage, and whether they have churned (left the service). It includes categorical and numerical features that need preprocessing before modeling.


Data Preprocessing

Load the dataset using pandas.

Handle missing values.

Encode categorical variables using LabelEncoder.

Balance the dataset using SMOTE (Synthetic Minority Over-sampling Technique).

Split the dataset into training and testing sets.

Machine Learning Models Used

The following models are used for predicting churn:

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

Model Evaluation

The models are evaluated using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Cross-validation for model stability

Usage

Clone the repository:

git clone https://github.com/yourusername/customer-churn-prediction.git

Navigate to the project directory:

cd customer-churn-prediction

Run the Python script:

python churn_prediction.py

Results

The performance of different models is compared based on accuracy and other evaluation metrics.

The best-performing model can be used to make predictions on new customer data.

Contributing

Feel free to fork this repository, improve the models, or add new features. Contributions are welcome!

License

This project is licensed under the MIT License.

Contact

For any inquiries or collaborations, reach out to Srijita Majumder via email or GitHub.

