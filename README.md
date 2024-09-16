# Diabetes Readmission Prediction

## Overview

This project aims to predict hospital readmission rates for patients hospitalized with diabetes. By identifying high-risk patients early in their hospitalization, we can help reduce readmission rates and improve hospital quality.

## Problem Statement

Hospital readmissions have been a focus of healthcare quality improvement for decades. This project specifically addresses readmissions for diabetic patients, aiming to identify key factors that contribute to higher readmission rates.

## Research Questions

1. What methods can best predict hospital readmission in this dataset?
2. What are the strongest predictors of hospital readmission in diabetic patients?

## Methodology

We employed several machine learning algorithms to predict readmission rates:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Each algorithm was evaluated using 10-fold stratified cross-validation and the area-under-the-curve (AUC) metric.

## Key Findings

- XGBoost performed best, achieving 94% accuracy and 0.61 AUC
- Random Forest was the second-best model with 92% accuracy and 0.94 AUC
- Most important factors influencing readmission:
  - Length of hospital stay
  - Number of inpatient stays
  - Number of diagnoses

## Data Files

The project uses three CSV files:

1. `diabetic_data.csv`
2. `modified_diabetes1205_beforeEDA.csv`
3. `smote_data.csv`

