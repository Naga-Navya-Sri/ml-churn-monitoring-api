🚧 This project is currently under active development.
Upcoming improvements:
- Dockerization
- Cloud deployment
- CI/CD integration

# ML Churn Monitoring API

Production-style machine learning system for customer churn prediction with calibrated classification, threshold optimization, FastAPI deployment, explainability, and data drift monitoring.

---

## 🚀 Project Overview

This project simulates a real-world ML system for customer churn prediction.

It goes beyond notebook modeling by implementing:

- Synthetic data generation with controlled behavioral patterns
- Advanced feature engineering
- Calibrated classification (Isotonic Calibration)
- Optimal threshold tuning (F1 maximization)
- Model persistence (joblib + metadata)
- REST API deployment using FastAPI
- Public exposure using ngrok
- Explainability endpoint
- Data drift monitoring using Population Stability Index (PSI)

The goal is to demonstrate end-to-end ML system thinking rather than just model training.

---

## 🧠 ML Pipeline Architecture

1. Synthetic Data Generation
2. Feature Engineering
3. Train / Validation / Test Split
4. Logistic Regression (class-balanced)
5. Probability Calibration
6. Threshold Optimization
7. Model + Metadata Saving
8. API Deployment
9. Monitoring & Explainability

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

### Prediction


Returns:
- churn_probability
- churn_prediction
- threshold

### Explainability


Returns:
- PSI score per numeric feature

---

## 🛠 Tech Stack

- Python
- scikit-learn
- FastAPI
- Uvicorn
- pyngrok
- Pandas
- NumPy

---

## 📦 Deployment Simulation

The API is exposed publicly using ngrok to simulate production-style external access.

Example:


Swagger UI is available for interactive testing.

---

## 📈 Why This Project Matters

Most ML projects stop at training a model.

This project demonstrates:

- Probability calibration awareness
- Decision threshold tuning
- API-based inference serving
- Model explainability
- Data drift monitoring
- Deployment simulation

It reflects ML engineering mindset rather than just data science experimentation.

---

## 🎯 Target Use Case

Telecom / SaaS customer churn prediction with monitoring-ready architecture.

---

## 👩‍💻 Author

Built as part of an end-to-end ML engineering portfolio project.
