# Loan Default Forecasting
This report is our machine learning course project. We experimented with different machine learning models, including Logistic Regression, Random Forest, and XGBoost, and applied various preprocessing techniques to improve benchmarks. When users enter their information (age, income, employment status, loan intent, etc.) into the model, it outputs the likelihood of loan default.

## Overview
**Dataset**: https://www.kaggle.com/datasets/nanditapore/credit-risk-analysis/data

**Problem**: The challenge of making informed decisions when extending credit.    

**Action**: We select several machine learning models such as **Logistic Regression**, **Random Forest**, and **XGBoost** to find out which benchmark model performs the best. Then, we improve the benchmark model with cross-validation, SMOTE, and other preprocessing techniques. Below are the before and after AUROC charts that showcase the model's improvement.

<img width="299" alt="image" src="https://github.com/wenchitseng/loan_default_forecasting/assets/145182368/3adaa3ad-7338-4fe4-aa2f-ad1e931c08df">
<img width="282" alt="image" src="https://github.com/wenchitseng/loan_default_forecasting/assets/145182368/da227af7-91bd-4f6c-901f-48f2d0d2ee6f">

**Result**: The best-perfomring model is XGBoost.

