# Bank-Customer-Churn-Analysis-and-Prediction

Project Overview

Customer churn is a critical metric for banks, as retaining existing customers is far more cost-effective than acquiring new ones. This project analyzes bank customer data to identify key factors that lead to churn and builds a machine learning model to predict whether a customer is likely to leave.

Dataset

The dataset contains customer-level information including:

-Customer demographics (e.g., age, gender, geography).
- Account details (e.g., balance, active status, tenure).
- Services used (e.g., number of products, credit card usage).
- Churn label (Exited: 1 = left, 0 = stayed).

Project Goals

- Explore and visualize patterns in customer churn.
- Identify key features contributing to churn.
- Build predictive models to classify customer churn.
- Evaluate model performance using metrics like accuracy, precision, recall, and F1 score.

Technologies Used

- Python 3.10
- Pandas, NumPy – Data processing
- Matplotlib, Seaborn – Data visualization
- Scikit-learn – Model building
- XGBoost – Advanced classification

Exploratory Data Analysis (EDA)

- Checked for null/missing values.
- Visualized churn rate across demographics and services.
- Detected imbalances in target variable.
- Encoded categorical variables for modeling.

 Model Building

Trained and tested the following models:

- Logistic Regression.
- Random Forest Classifier.
- XGBoost Classifier.

 Used metrics like:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Curve

 Key Findings

- Customers with lower tenure, lower balance, and fewer products were more likely to churn.
- Geographic location and active membership status had strong correlation with churn.
- XGBoost achieved the highest accuracy and recall for churn prediction.

 Results

Model: Logistic Regression

- Accuracy: 81%
- Precision: 76%
- Recall: 66%
- F1 Score: 70%

Model: Random Forest

- Accuracy: 86%
- Precision: 82%
- Recall: 72%
- F1 Score: 77%

Model: XGBoost

- Accuracy: 88%
- Precision: 84%
- Recall: 75%
- F1 Score: 79%

 Future Improvements

- Handle class imbalance using SMOTE.
- Add more customer behavioral data (e.g., transactions).
- Perform feature selection/engineering.
- Deploy a dashboard for real-time churn prediction.


