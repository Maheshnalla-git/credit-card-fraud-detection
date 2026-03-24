# Credit Card Fraud Detection

## Project Overview
This project builds a machine learning model to detect fraudulent credit card transactions using a real-world Kaggle dataset.

## Dataset
- 284,807 transactions
- Highly imbalanced dataset
- Target column: Class (0 = Normal, 1 = Fraud)

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SMOTE

## Steps Performed
1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Data splitting
4. Model training (Logistic Regression)
5. Handling imbalance using SMOTE
6. Model evaluation using confusion matrix and classification report

## Results
- Improved fraud detection recall from 63% to 90% using SMOTE
- Evaluated trade-off between precision and recall

## Conclusion
SMOTE significantly improved fraud detection capability, making the model more suitable for real-world fraud detection systems.