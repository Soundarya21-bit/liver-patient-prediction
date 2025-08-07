# Liver Patient Prediction
**Medical Diagnosis of Liver Disease using Machine Learning**

This classification project uses clinical patient data to predict the likelihood of liver disease.

---

## 🧾 Project Overview
Built as part of an internship project, the goal is to assist early diagnosis of liver conditions using classification algorithms.

---

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Features: Clinical data including enzyme levels, age, gender, etc.
- Target: `Dataset` (1 = Liver Disease, 2 = No Disease)

---

## ⚙️ Tools & Libraries
- Python  
- Pandas  
- Scikit-learn  
- LightGBM  
- Matplotlib / Seaborn  

---

## 🚀 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM ✅ *(Final Selected Model)*

---

## ✅ Final Model Performance
- **Selected Model**: LightGBM  
- **Accuracy**: ~83%  
- **AUC Score**: ~86%  

---

## 📁 Files
- `Liver_Patient_Prediction_Final.ipynb`: Final cleaned notebook with EDA, modeling, ROC/AUC evaluation, and comments

---

## 📌 Summary
LightGBM performed best with high AUC and accuracy. It's suitable for handling the tabular structure and medical nature of the dataset.
