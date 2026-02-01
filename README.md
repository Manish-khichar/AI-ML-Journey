# AI-ML-Journey
[Open in Colab](https://colab.research.google.com/)


My step-by-step journey learning Machine Learning from scratch

This repository documents my step-by-step journey learning
Machine Learning from scratch using Python and Google Colab.

## Completed So Far
- Python tools for ML (NumPy, Pandas, Matplotlib)
- Linear Regression implemented from scratch
  - Mean Squared Error
  - Gradient Descent
  - Loss visualization

## Tools Used
- Python
- NumPy
- Matplotlib
- Google Colab

## Next Goals
- Multivariate Linear Regression
- Logistic Regression
- GitHub + Colab workflow

# Credit Card Fraud Detection using Machine Learning

##  Project Overview
This project builds an end-to-end Machine Learning pipeline to detect fraudulent credit card transactions using imbalanced financial data. The focus is on maximizing fraud recall while maintaining strong model reliability.

---

##  Objectives
- Detect fraudulent transactions accurately
- Handle severe class imbalance
- Compare multiple ML models
- Optimize threshold and recall
- Build explainable and deployable model

---

##  Models Used
- Logistic Regression (Weighted) — Final Selected Model
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

---

##  Techniques Applied
- Data preprocessing & EDA
- Train–test split with leakage prevention
- Feature scaling (StandardScaler)
- Class imbalance handling (class_weight)
- Threshold tuning
- Hyperparameter tuning (GridSearchCV)
- Model comparison using ROC-AUC & Recall
- Precision–Recall analysis
- Model explainability using coefficients
- Model saving using joblib

---

##  Evaluation Metrics
- ROC-AUC
- Precision
- Recall (Primary metric for fraud)
- F1-score
- Precision–Recall Curve

---

##  Key Outcome
Weighted Logistic Regression achieved the best balance of recall and ROC-AUC and was selected as the final deployable fraud detection model.

---

##  Model Deployment
Model and scaler saved using joblib for future inference.

---

##  Tools & Libraries
- Python
- Scikit-learn
- XGBoost
- LightGBM
- Pandas, NumPy
- Matplotlib

---

## Future Improvements
- Deep learning anomaly detection
- SHAP explainability
- Real-time scoring API
- Streaming fraud detection

---

##  Author
Manish Khichar

