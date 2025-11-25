# Early Prediction of Heart Disease Using Machine Learning (XGBoost + SMOTE)

This repository contains the research work and source code for a machine learning pipeline designed to predict early-stage heart disease using the Cleveland Heart Disease dataset. The project focuses on effective preprocessing, class imbalance handling, and model optimization to improve prediction accuracy.

## Overview

This project implements a complete workflow that includes:

- Data cleaning and preprocessing  
- Feature scaling and categorical encoding  
- Oversampling using SMOTE to address imbalance  
- Model training using XGBoost  
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix  
- Jupyter notebook demonstrating the full implementation  

The resulting model achieves strong performance and can serve as a foundation for clinical decision-support systems.

## Files in This Repository

- mlre.ipynb – Main Jupyter notebook with code  
- Early Prediction of Heart Disease.docx – Research paper (if included)  
- README.md – Project documentation  

(You can add a data/ folder if you upload the dataset to the repository.)

## Dataset

The project uses the Cleveland Heart Disease dataset, which includes:

- 303 patient records  
- 13 clinical features (age, sex, chest pain type, cholesterol, blood pressure, etc.)  
- Target variable indicates the presence (1) or absence (0) of heart disease  

The dataset is preprocessed to convert the original multi-class target into a binary classification problem.

## Methodology

### Preprocessing
- Handling missing values  
- Separating numerical and categorical features  
- Applying StandardScaler to numerical columns  
- Applying one-hot encoding to categorical columns  
- Using ColumnTransformer and Pipeline for structured processing  

### Handling Class Imbalance
- SMOTE applied only to the training dataset  

### Model Training
- XGBoost classifier used as the primary model  
- Parameters adjusted for stability and performance  

### Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrix  

## Results

Based on experiments included in the research:

- Accuracy: approx. 84.78%  
- Precision: approx. 85%  
- Recall: approx. 75%  
- F1-score: approx. 80%  

The combination of SMOTE and XGBoost significantly improves performance on imbalanced clinical datasets.
