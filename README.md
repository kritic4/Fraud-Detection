# Fraud Detection System

A machine learning based **Fraud Detection System** designed to identify fraudulent transactions in highly imbalanced datasets.  
This project combines a trained model with a **Streamlit web interface** to provide an interactive and user-friendly way to test and visualize fraud detection results.  

---

## Features

- Streamlit UI for end-users to upload transaction data and check fraud predictions.  
- Fraud classification model trained on imbalanced data with precision-recall and ROC evaluation.  
- Evaluation tools included: Confusion Matrix, ROC Curve, Classification Report, Outlier Detection.  
- Handles class imbalance with focus on recall (catching maximum fraud cases).  
- Outlier analysis in transaction amounts for better interpretability.  

---

## Model Performance

- Accuracy: 95%  
- ROC-AUC Score: 0.99  
- Recall (Fraud class): 0.94  
- Precision (Fraud class): 0.02  

---

## Streamlit UI

The Streamlit app allows users to:  
- Upload a transaction dataset in CSV format.  
- Get instant fraud prediction for each record.  


To run the UI locally:  

```bash
streamlit run app.py
