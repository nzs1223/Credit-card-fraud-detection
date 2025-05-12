# Credit-card-fraud-detection

Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. We utilize a classification approach to predict whether a transaction is fraudulent (1) or not fraudulent (0) based on various features. The dataset contains a class imbalance, with non-fraudulent transactions far outnumbering fraudulent ones.

Dataset
The dataset used in this project contains transaction details from credit card companies. ### Dataset
The dataset used for this project is the **Credit Card Fraud Detection** dataset, which is available for download from the following link:

[Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

*Note: You will need to sign in to Kaggle to access the dataset.*
 It includes features such as:

Transaction Amount

Merchant Type

Time of Transaction

Features (PCA transformed for privacy reasons)

Target label (1 for fraud, 0 for non-fraud)

This dataset can be found at Kaggle - Credit Card Fraud Detection.

Steps Taken
Data Loading:

Loaded the dataset and inspected it for missing values or any data quality issues.

Data Preprocessing:

Handled missing values, if any.

Applied scaling to numerical features using StandardScaler to normalize the data.

Addressed class imbalance using resampling techniques.

Exploratory Data Analysis (EDA):

Performed an initial examination of the data, including plotting the distribution of the target variable.

Investigated the imbalance in the target classes and understood the feature distributions.

Model Building:

Chose a Random Forest classifier for its ability to handle imbalanced datasets and its performance on tabular data.

Split the dataset into training and test sets using an 80-20 ratio.

Model Evaluation:

Evaluated the model using classification metrics such as Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC AUC Score.

Model performance showed high accuracy with good recall for detecting fraudulent transactions.

Final Model:

The model achieved an accuracy of 100%, with high precision and recall scores for detecting fraud, though the class imbalance affected the precision for fraudulent transactions.

Key Performance Metrics
Accuracy: 1.00 (100%)

Precision (Fraudulent): 0.83

Recall (Fraudulent): 0.65

F1-Score (Fraudulent): 0.73

ROC AUC Score: 0.956

Confusion Matrix
lua
Copy
Edit
[[56851    13]
 [   34    64]]
Files Included
netflix_recommender.ipynb: The Jupyter Notebook that includes the data processing, model building, and evaluation.

credit_card_fraud_dataset.csv: The dataset used for the project.

README.md: This README file describing the project.
