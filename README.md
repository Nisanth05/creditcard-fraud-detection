# Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions in credit card data using machine learning techniques. The dataset used is highly imbalanced, which is a common issue in fraud detection, so techniques like SMOTE (Synthetic Minority Oversampling Technique) are applied to improve performance.

## Dataset

The dataset is taken from Kaggle and contains transactions made by European cardholders in September 2013, with 284,807 transactions, of which only 492 are frauds.

You can find the dataset [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Project Highlights

- Data Preprocessing:
  - Scaled Time and Amount using StandardScaler
  - Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique)

- Models Used:
  - Logistic Regression
  - Random Forest Classifier

- Evaluation Metrics:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
  - ROC AUC Score
  - ROC Curve Visualization

## Results

- Logistic Regression:
  - ROC AUC Score: ~0.969
  - High recall on fraud detection (92%), but low precision

- Random Forest:
  - ROC AUC Score: ~0.973
  - High precision and recall for both classes

## Conclusion

Random Forest outperformed Logistic Regression in terms of precision, recall, and AUC. It is a better choice for fraud detection tasks, especially in handling imbalanced data.


