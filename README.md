#  Task 3 - Customer Churn Prediction (CodSoft Internship)

This project predicts whether a customer will churn (leave the bank) using Logistic Regression with feature scaling and model evaluation.






##  Dataset

- Banking dataset containing customer records like `CreditScore`, `Age`, `Balance`, `Geography`, `Gender`, and `Exited`
- Target variable: `Exited` (1 = churned, 0 = stayed)
- Preprocessing included:
  - Dropping `CustomerId`, `Surname`, and `RowNumber`
  - Encoding `Gender` using LabelEncoder
  - One-hot encoding `Geography` using `pd.get_dummies`
## Tools

- Python
- pandas, numpy
- scikit-learn:
  - LogisticRegression
  - StandardScaler
  - train_test_split
  - Evaluation Metrics


## Steps performed

1. Cleaned and encoded the dataset
2. Split into training and test sets
3. Applied **StandardScaler** to normalize features
4. Trained a **Logistic Regression** model
5. Evaluated using:
   - Classification Report
   - Confusion Matrix
   - ROC AUC Score
## Results
- Balanced model to reduce bias toward majority class
- Achieved good ROC AUC score indicating model discrimination power
