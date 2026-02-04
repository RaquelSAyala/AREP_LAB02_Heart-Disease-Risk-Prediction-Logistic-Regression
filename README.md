# Heart Disease Risk Prediction – Logistic Regression

#### Author: Raquel Selma
#### Escuela Colombiana de Ingeniería Julio Garavito
#### Arquitecturas Empresariales

---
## Repository Overview
This repository contains a complete implementation of **logistic regression from scratch** for predicting heart disease risk using clinical data.  
The project follows an end-to-end machine learning workflow, including data exploration, model training, visualization, regularization, and deployment exploration using Amazon SageMaker.

---

## Exercise Summary
Implements logistic regression for heart disease prediction: **EDA, training/visualization, regularization, and SageMaker deployment**.

---

## Dataset Description
- **Dataset:** Kaggle Heart Disease Dataset  
- **Source:** https://www.kaggle.com/datasets/neurocipher/heartdisease  
- **Samples:** 303 patients  
- **Features:** 13 clinical features + 1 binary target  
- **Examples of features:**  
  - Age (29–77 years)  
  - Cholesterol (112–564 mg/dL)  
  - Resting Blood Pressure  
  - Maximum Heart Rate  
  - ST Depression  
  - Number of Major Vessels  
- **Target Variable:**  
  - 1 → Presence of heart disease  
  - 0 → Absence of heart disease  
- **Class Distribution:** Approximately **55% presence rate**

---

## Notebook Contents
Main analysis is contained in:

- `LAB02_Heart Disease Risk Prediction.ipynb`

The notebook includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing and normalization
- Logistic Regression implemented from scratch
- Gradient Descent optimization
- Cost convergence plots
- Decision boundary visualization
- L2 regularization (Ridge)
- Model export for deployment

---

## Model Training and Visualization Evidence

### Training Cost Convergence

<img width="689" height="783" alt="image" src="https://github.com/user-attachments/assets/2d4fbdfb-8389-4d86-b10b-8279bb99a755" />

<img width="647" height="503" alt="image-1" src="https://github.com/user-attachments/assets/511c8487-b6ab-45cf-ae6b-69a2d7cd1b25" />

<img width="601" height="491" alt="image-3" src="https://github.com/user-attachments/assets/5b6eaa3e-466b-46c4-832d-f196e00c181d" />

<img width="623" height="474" alt="image-5" src="https://github.com/user-attachments/assets/843f1e5c-ccb3-4ed0-a193-4eb566c591f1" />

<img width="591" height="484" alt="image-7" src="https://github.com/user-attachments/assets/03c480ea-1336-4c1b-a4f9-5774f6e37f61" />


### Decision Boundary Visualizations

<img width="604" height="478" alt="image-2" src="https://github.com/user-attachments/assets/0bcc6761-a241-4735-b484-a7a070c8a036" />

<img width="593" height="466" alt="image-4" src="https://github.com/user-attachments/assets/9b59d9c1-395f-4eb2-97d3-030d8a4ae13e" />

<img width="638" height="481" alt="image-6" src="https://github.com/user-attachments/assets/8996a897-a64d-4f75-9878-0606fcf6dd3a" />

---

## Repository Structure
```
├── LAB02_Heart Disease Risk Prediction.ipynb
├── Heart_Disease_Prediction.csv
├── best_logreg_model.json
├── README.md
└── images/
    ├── cost_convergence.png
    ├── decision_boundary_1.png
    ├── sagemaker_training_job.png
    ├── sagemaker_endpoint_config.png
    └── inference_response.png
```

---

## GitHub Repository
```
https://github.com/RaquelSAyala/AREP_LAB02_Heart-Disease-Risk-Prediction-Logistic-Regression
```
