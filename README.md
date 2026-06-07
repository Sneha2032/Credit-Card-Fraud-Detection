Credit Card Fraud Detection Using Machine Learning

This project aims to detect fraudulent credit card transactions using Machine Learning techniques. Due to the highly imbalanced nature of the dataset, undersampling was performed to create a balanced dataset for model training. A Logistic Regression classifier was trained to distinguish between legitimate and fraudulent transactions based on transaction features.

Features
Data preprocessing and cleaning
Missing value analysis
Exploratory Data Analysis (EDA)
Handling class imbalance using undersampling
Train-test data splitting
Logistic Regression model training
Model evaluation using accuracy metrics
Dataset
The dataset contains credit card transactions represented by anonymized features (V1–V28), along with Time, Amount, and Class labels:

Class 0 → Legitimate Transaction
Class 1 → Fraudulent Transaction
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Google Colab
Results
Training Accuracy: 97.48%
Testing Accuracy: 98.32%
Future Improvements
Apply advanced models such as Random Forest, XGBoost, and LightGBM
Evaluate using Precision, Recall, F1-Score, and ROC-AUC
Deploy the model as a web application using Flask or Streamlit

