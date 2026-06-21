# Loan Approval Prediction

## Dataset
Kaggle - Loan Approval Prediction Dataset
Link: https://www.kaggle.com/datasets/bhanupratapbiswas/loan-approval-prediction-case-study

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SMOTE

## Models Built
- Logistic Regression
- Random Forest Classifier

## Key Findings
- Credit History is the strongest predictor
- Random Forest outperforms Logistic Regression
- SMOTE used to handle class imbalance
- Recommended deployment threshold: 0.4

## Visualizations
- EDA Charts (Loan Status, Education, Credit History, Loan Amount)
- ROC Curve Comparison
- Feature Importance Chart

## Business Recommendations
1. Deploy Random Forest for loan predictions
2. Focus on Credit History verification
3. Manually review borderline cases (0.4-0.6 probability)
4. Re-train model every 6 months with new data

## Deliverables
- Jupyter Notebook with modeling pipeline and metrics
- PDF report discussing model trade-offs and deployment threshold
