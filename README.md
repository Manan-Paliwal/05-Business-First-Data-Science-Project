# Loan Approval Prediction System

An end-to-end classification project that applies machine learning to loan-application data and demonstrates how predictive modeling can support data-driven lending workflows.

> **Note:** This is an educational portfolio project, not a production credit-decision system.

## Objective

Predict the dataset's `Loan_Status` target from applicant information using a supervised machine-learning pipeline.

## Problem Framing

Loan decisions involve balancing financial risk with access to credit. This project explores how structured applicant data can be prepared and modeled to produce a baseline approval prediction.

## Workflow

1. Business-problem definition
2. Data loading and inspection
3. Missing-value handling
4. Exploratory data analysis
5. Feature preparation
6. Categorical encoding
7. Train-test split
8. Model training
9. Model evaluation
10. Business interpretation

## Model

The project uses a **Random Forest Classifier** as its primary prediction model.

## Reported Performance

| Metric | Result |
|---|---:|
| Accuracy | **74.80%** |

Accuracy is useful as a baseline summary, but a real lending system would require deeper analysis of class-level errors, fairness, calibration, stability, and the cost of incorrect decisions.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Structure

```text
05-Business-First-Data-Science-Project/
├── data/
├── images/
├── notebooks/
├── outputs/
├── reports/
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

## Skills Demonstrated

- Business-first ML framing
- Data cleaning
- Feature preparation
- Classification
- Random Forest
- Model evaluation
- Translating model output into business context

## Important Limitations

This project should be treated as a learning exercise rather than an automated lending decision system. A production-grade system would need:

- More complete classification metrics
- Cross-validation
- Bias and fairness assessment
- Model calibration
- Robust feature governance
- Explainability and auditability
- Regulatory and domain review

## Future Improvements

- Compare Logistic Regression, XGBoost, and other classifiers
- Add precision, recall, F1, ROC-AUC, and PR-AUC
- Perform cross-validation
- Tune hyperparameters
- Add model interpretability
- Analyze class imbalance
- Add fairness checks
- Build a small inference interface

---

**Author:** Manan Paliwal  
B.Tech Computer Science Engineering — Artificial Intelligence & Machine Learning
