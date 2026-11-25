# Customer Churn Prediction: A Comparative Study of Class Imbalance Strategies

A machine learning study on the Telco Customer Churn dataset (7,043 customers) that benchmarks 16 model and strategy combinations: Logistic Regression (with PCA), Random Forest, XGBoost and CatBoost, each trained with the original data, SMOTE, NearMiss undersampling and class weighting.

**Highlights**
- Class-weighted CatBoost performed best: F1 0.6254, churn recall 81.02%, ROC-AUC 0.8396
- Baseline models reached about 79% accuracy but missed nearly half of the churners (recall about 50–53%)
- NearMiss undersampling hurt performance for every model
- Contract type, tenure and monthly charges were among the strongest churn signals

**Tech:** Python, pandas, scikit-learn, imbalanced-learn, XGBoost, CatBoost, Matplotlib, Seaborn

Course project for CSE427, BRAC University.
