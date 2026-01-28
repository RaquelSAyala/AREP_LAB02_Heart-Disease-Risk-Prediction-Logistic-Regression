# Heart Disease Risk Prediction – Logistic Regression (From Scratch)

##  Exercise Summary
This project implements a **logistic regression model from scratch** to predict the risk of heart disease using clinical data.  
The workflow follows an end-to-end machine learning pipeline including:

- Exploratory Data Analysis (EDA)
- Data preprocessing and normalization
- Logistic Regression implemented manually (no scikit-learn for training)
- Model evaluation with classification metrics
- Decision boundary visualization
- L2 regularization (Ridge)
- Model export and deployment exploration using **Amazon SageMaker**

The goal is to demonstrate both theoretical understanding and practical application of logistic regression in a healthcare context.

---

## Dataset Description
- **Dataset:** Heart Disease Prediction Dataset (Kaggle)
- **Source:** https://www.kaggle.com/datasets/neurocipher/heartdisease
- **Samples:** 270 patients
- **Features:** 13 clinical attributes + 1 target
- **Target Variable:**  
  - `Heart Disease = Presence` → 1  
  - `Heart Disease = Absence` → 0
- **Disease Rate:** ~44% Presence, ~56% Absence

### Selected Features for Modeling
At least 6 features were selected, as required by the lab:
- Age
- Cholesterol
- Blood Pressure (BP)
- Max Heart Rate
- ST Depression
- Number of Vessels (fluro)

---
