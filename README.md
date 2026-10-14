# Adult Census Income Prediction

End-to-end classification project built during NTI ML Summer Training (2026). It predicts whether a person earns more than $50K per year.

## Dataset
Kaggle Adult Census Income dataset (32,561 records).

## What I did
- Compared six models: Random Forest, Decision Tree, Naive Bayes, SVC, Logistic Regression, KNN
- Built a ColumnTransformer preprocessing pipeline (imputation, scaling, one-hot encoding)
- Compared log-transform vs. IQR outlier removal for skewed features
- Evaluated with precision, recall, F1-score and ROC-AUC

## Result
Up to 80.6% test accuracy.

## Tools
Python, Pandas, NumPy, scikit-learn, Google Colab
