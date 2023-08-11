# Credit_Card_Fraud_Detection
Credit Card Fraud Detection:

This project aims to develop a machine learning model to detect fraudulent credit card transactions. The model is trained on a dataset containing labeled transactions, where each transaction is classified as either fraudulent or legitimate. There are several machine learning algorithms that can be used for credit card fraud detection, including Logistic Regression, decision trees, random forests, Gradient Boosting and Support Vector Machines.

Dataset:

The Credit Card Fraud Detection dataset from Kaggle is used for this project. It includes credit card transactions made by European cardholders in September 2013. The dataset covers a two-day period and contains 284,807 transactions, of which 492 are fraudulent. The dataset is highly imbalanced, with frauds accounting for only 0.172% of all transactions. The dataset includes anonymized credit card transactions with features such as transaction amount, time, and various transformed features. The features V1, V2, … V28 are principal components obtained through PCA. The only features not transformed by PCA are ‘Time’ and ‘Amount’. The ‘Time’ feature represents the seconds elapsed between each transaction and the first transaction in the dataset. The ‘Amount’ feature represents the transaction amount. The response variable is the ‘Class’ feature, which takes the value 1 for fraud and 0 otherwise.

Installation:

To run this project, follow these steps:

Clone the repository: git clone https://github.com/geetika-0812/Credit_Card_Fraud_Detection.git Install the required dependencies: pip install matplotlib Download the dataset mentioned with the name of creditcard.csv

Results:

The Random Forest model achieved a precision of 90.5882%, recall of 84.6154%, F1-score of 87.5%, and AUPRC score of 76.6793%. These metrics indicate the best model’s performance in detecting fraudulent transactions. Rest all models have metric less than this one for the corresponding categories respectively.

Future Work:

Some potential areas for future improvement and expansion of this project include:

Exploring different machine learning algorithms and implementing artifical neural networks techniques for fraud detection. Implementing real-time fraud detection using streaming data. Investigating feature engineering techniques to improve model performance. Deploying the model as an API for real-time predictions.

Contributing:

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
