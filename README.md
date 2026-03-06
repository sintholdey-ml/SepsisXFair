# SepsisXFair: Interpretable Sepsis Prediction with XGBoost and SHAP
SepsisXFair is a machine learning project for early prediction of sepsis using ICU time-series data and interpretable models (XGBoost + SHAP).  
The goal is to build a clinically meaningful and explainable risk prediction pipeline.

# About
SepsisXFair is a Google Colab–based ML pipeline for early sepsis onset prediction from routine EHR data using LR, XGBoost and LightGBM with preprocessing, threshold tuning (0.4), SHAP explainability (XAI), calibration and age/gender subgroup fairness evaluation.

## 1. Project Overview

- **Task:** Binary classification – predict sepsis onset (SepsisLabel).  
- **Data:** ICU patient time-series data (vitals, labs, demographics).  
- **Model:** XGBoost classifier with careful preprocessing (imputation, variance filtering, scaling).  
- **Explainability:** Global feature importance + SHAP values for per-patient and global explanations.

## 2. Dataset

The main dataset is too large for direct GitHub upload, so it is hosted externally.

- **File:** `Dataset.csv` (≈146 MB)  
- **Location:** Google Drive 
- **Download link:**   https://drive.google.com/file/d/1ip3taJCoowY8le6pyoIgfAeZApOi9X41/view?usp=sharing


