# ML Churn Monitoring API

Production-style machine learning system for customer churn prediction with calibrated classification, threshold optimization, FastAPI deployment, explainability, and data drift monitoring (PSI).

---

## 🚀 Project Overview

This project simulates a real-world ML system for churn prediction.

Instead of stopping at model training, it implements:

- Synthetic data generation
- Feature engineering
- Calibrated Logistic Regression (Isotonic)
- F1-score based threshold tuning
- Model persistence (joblib)
- REST API deployment using FastAPI
- Public exposure using ngrok
- Explainability endpoint
- Drift detection using PSI

The focus is on ML system design, not just notebook experimentation.

---

## 🧠 ML Pipeline

1. Synthetic Data Generation  
2. Feature Engineering  
3. Train / Validation / Test Split  
4. Logistic Regression (class-balanced)  
5. Probability Calibration  
6. Threshold Optimization  
7. Model + Metadata Saving  
8. API Deployment  
9. Explainability & Monitoring  

---

## 📊 Model Details

- Algorithm: Logistic Regression
- Class Handling: Balanced class weights
- Calibration: Isotonic regression
- Threshold Optimization: F1-score maximization
- Evaluation Metrics:
  - ROC-AUC
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## 🌐 API Endpoints

### Health Check
