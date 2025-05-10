
# 🧠 Alzheimer's Disease Risk Prediction – Capstone Project

This capstone project uses machine learning to predict the risk of Alzheimer's disease based on a synthetic dataset of 74,283 individuals from 20 countries. The dataset includes demographic, lifestyle, medical, cognitive, and genetic features.

We trained and evaluated several models, with **Gradient Boosting** selected as the final model due to its superior recall and AUC—critical in medical applications where minimizing false negatives is key.

## 📌 Key Insights
- **Age** is the most significant predictor of Alzheimer's risk.
- Individuals with **diabetes**, **hypertension**, or **high cholesterol** showed higher diagnosis rates.
- **Family history** and the **APOE-ε4 genetic marker** were strong risk indicators.
- **Education level** showed a moderate protective effect, possibly due to cognitive reserve.

## ✅ Final Model (Gradient Boosting)
- **Accuracy**: 72.3%  
- **Recall**: 71.8%  
- **F1-Score**: 68.2%  
- **ROC-AUC**: 0.7975

## 🚀 Deployment
A Streamlit web app was developed to allow users to input personal and lifestyle factors and receive a real-time Alzheimer's risk prediction.

🔗 [Try the App](https://alzheimerdiagnosis.streamlit.app/)

> ⚠️ *Note: This tool is based on synthetic data and is for educational purposes only. It is not intended for clinical use.*
