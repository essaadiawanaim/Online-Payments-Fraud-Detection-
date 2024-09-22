# detection of fraud in online transactions
#### Fraud Detection using Machine Learning

This project applies various Machine Learning (ML) techniques to detect fraud in online payment transactions. The models implemented include Logistic Regression, Random Forest, and XGBoost. The dataset is highly imbalanced, and techniques like SMOTE and undersampling were used to handle this imbalance. 

## Key Features:
- **Data Preprocessing:** Handled missing values, categorical encoding, and applied feature scaling using RobustScaler.
- **Modeling Approaches:** Logistic Regression, Random Forest, and XGBoost with hyperparameter tuning using GridSearchCV.
- **Handling Class Imbalance:** Techniques like oversampling and undersampling were applied.
- **Evaluation Metrics:** Precision, Recall, F1-Score, and ROC-AUC.
- **Results:** The Random Forest model showed superior performance with an MCC of 0.27 and ROC-AUC of 0.95.

## Dataset:
We used a dataset from Kaggle containing 6 million transactions, out of which 8312 were labeled as fraud.

## Conclusion:
The Random Forest model performed best for detecting fraudulent transactions, but with a higher false positive rate. The logistic regression model was more conservative with false positives but missed more fraud cases.

## References:
- **University:** Abdelmalek Essaadi University
- **Supervisor:** Pr. Khamjane
  

[Link to the full report](/main/ML-Rapport.pdf)


https://github.com/essaadiawanaim/Online-Payments-Fraud-Detection-/blob/main/ML-Rapport.pdf
