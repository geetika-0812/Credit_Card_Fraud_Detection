# Credit_Card_Fraud_Detection
Credit Card Fraud Detection:
A machine learning model to identify fraudulent credit card transactions is what this project attempts to create. The model is developed using a dataset of labelled transactions, where each transaction is assigned to either a fraudulent or valid category. Logistic regression, decision trees, random forests, gradient boosting, and support vector machines are a few examples of machine learning techniques that can be used to detect credit card fraud.


Dataset:

This project makes use of the Kaggle Credit Card Fraud Detection dataset. It comprises credit card transactions performed in September 2013 by cardholders across Europe. 284,807 transactions total in the dataset over a two-day span, 492 of which are fake. With only 0.172% of all transactions being fraudulent, the dataset is severely unbalanced. The dataset contains de-identified credit card transactions including information on the amount, date, and other altered attributes. Principal components (PCA) were used to determine the characteristics V1, V2,... V28. The only attributes that PCA does not alter are "Time" and "Amount." The 'Time' feature shows the number of seconds that passed between each transaction and the dataset's initial transaction. The ‘Amount’ feature represents the transaction amount. The response variable is the ‘Class’ feature, which takes the value 1 for fraud and 0 otherwise.

Installation:

To run this project, follow these steps:

Clone the repository: git clone https://github.com/geetika-0812/Credit_Card_Fraud_Detection.git Install the required dependencies: pip install matplotlib Download the dataset mentioned with the name of creditcard.csv

Results:

The Random Forest model achieved a precision of 90.5882%, recall of 84.6154%, F1-score of 87.5%, and AUPRC score of 76.6793%. These metrics indicate the best model’s performance in detecting fraudulent transactions. Rest all models have metric less than this one for the corresponding categories respectively.

Future Work:

This project may be enhanced and expanded in the future in the following ways:

investigating various machine learning techniques and applying artificial neural network methods for fraud detection. leveraging streaming data to implement real-time fraud detection. looking into feature engineering methods to enhance model performance. Using the model as a real-time prediction API.

Contributing:

This project is open to suggestions. Please raise an issue or submit a pull request if you discover any problems or have ideas for improvement.
