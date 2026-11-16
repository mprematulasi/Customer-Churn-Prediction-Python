# Customer-Churn-Prediction-Python (Python & Machine Learning)
Machine learning classification project predicting bank customer churn with 86.65% accuracy using python and Random Forest

## Project Overview
A supervised machine learning project analyzing 10,000 bank customer records (Churn_Modelling.csv) to predict customer attrition and identify key churn drivers, achieving *86.65% test accuracy*.

## Tools & Techniques Used
* *Python Libraries:* Pandas, NumPy, Scikit-learn
* *Data Preprocessing:* Missing-value verification, one-hot encoding (pd.get_dummies) for categorical variables (Geography, Gender), and dropping non-predictive identifier columns.
* *Feature Scaling & Split:* 80/20 train-test split (random_state=42) with StandardScaler applied properly to prevent data leakage.
* *Modeling & Evaluation:* Trained a *Random Forest Classifier* (n_estimators=100, criterion='gini') and evaluated performance using accuracy_score.

## Key Business Insights
* Built a reliable classification pipeline capable of flagging high-risk customers before they discontinue their banking relationship.
* Enabled proactive customer retention strategies based on account balance, credit score, tenure, age, and product holdings.
