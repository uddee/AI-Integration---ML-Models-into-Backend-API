# AI-Integration ML Models into Backend-API
# 🧠 Fraud Detection API

This project integrates a machine learning model into a backend API with ETL preprocessing to detect fraudulent transactions. It automates preprocessing, prediction, and deployment — and is ideal for real-time or batch fraud detection.

---

## 📦 Features

- ✅ ETL preprocessing pipeline (pandas)
- ✅ ML model (RandomForestClassifier)
- ✅ FastAPI REST API
- ✅ Jupyter Notebook-compatible
- ✅ Cloud-ready with Docker (optional)

---

## 🏗️ Architecture

```text
+-------------------+
| Incoming Request  |
+-------------------+
          |
          v
+-------------------+
|     ETL Step      | --> Preprocess transaction data
+-------------------+
          |
          v
+-------------------+
|   ML Prediction   | --> Predict fraud (0 or 1)
+-------------------+
          |
          v
+-------------------+
|     API Output    | --> JSON: {"fraud": true}
+-------------------+
