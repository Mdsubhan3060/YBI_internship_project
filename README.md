# YBI_internship_project
Bank Customer Churn Prediction
This project aims to predict customer churn in a bank using machine learning algorithms. By analyzing customer data, we can identify those at high risk of leaving the bank and take proactive steps to retain them. The project uses Logistic Regression and Support Vector Machine (SVM) to create predictive models based on key customer features.

Project Overview
Customer churn prediction is essential for banks to maintain a loyal customer base and reduce revenue loss. This project explores the following:

Data Preprocessing: Cleaning and transforming the dataset for model training.
Exploratory Data Analysis (EDA): Understanding patterns in attributes such as Credit Score, Balance, Tenure, and Age.
Modeling: Implementing Logistic Regression and SVM to predict churn.
Model Evaluation: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.
Dataset
The dataset includes various features of bank customers, such as:

CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
IsActiveMember
EstimatedSalary
Exited (target variable indicating churn)
Project Structure
bash
Copy code
├── data/                       # Dataset folder
├── notebooks/                  # Jupyter notebooks for EDA and model training
├── src/                        # Python scripts for data preprocessing, modeling, and evaluation
├── README.md                   # Project description and instructions
└── requirements.txt            # Required libraries
Requirements
Install project dependencies using:

bash
Copy code
pip install -r requirements.txt
Approach
Data Preprocessing: Cleaned and transformed the dataset, including handling missing values, encoding categorical features, and scaling numerical data.
EDA: Analyzed feature distributions and correlations to understand the data.
Modeling:
Logistic Regression: A simple, interpretable model for binary classification.
SVM: Used a Support Vector Machine to improve classification performance.
Evaluation: Compared models on accuracy, precision, recall, and F1-score to select the best-performing approach.
Results
Both Logistic Regression and SVM models were evaluated on their effectiveness in predicting customer churn. Key performance metrics are summarized as follows:

Logistic Regression: Accuracy = X%, Precision = Y%, Recall = Z%
SVM: Accuracy = A%, Precision = B%, Recall = C%
Conclusion
This project provides a framework for predicting customer churn in banking using Logistic Regression and SVM. By identifying at-risk customers, banks can target their retention efforts more effectively and improve overall customer satisfaction.

Future Work
Experiment with additional algorithms like Random Forest and XGBoost for improved accuracy.
Implement hyperparameter tuning to optimize model performance.
Apply deep learning models for more complex feature interactions.


