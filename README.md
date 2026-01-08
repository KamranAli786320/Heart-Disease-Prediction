# ❤️ Heart Disease Prediction

This project implements a **Machine Learning model** to predict whether a person is at risk of **heart disease** based on medical, lifestyle, and demographic factors.

---

## 📋 Project Overview

Heart disease is one of the leading causes of death worldwide.  
The goal of this project is to build a **predictive ML system** that analyzes patient health data and predicts **Heart Disease Status (Yes/No)**.

- Dataset Size: **10,000 records**
- Features: **21 health-related attributes**
- Output: **Binary classification**

---

## 🗂️ Dataset Information

### 👤 Demographic Information
- Age: 18–80 years  
- Gender: Male / Female  

### 🏥 Medical History & Conditions
- Blood Pressure: 120–180 mmHg  
- Cholesterol Level: 150–300 mg/dL  
- Diabetes: Yes / No  
- High Blood Pressure: Yes / No  
- Family Heart Disease: Yes / No  
- BMI: 18–40  

### 🏃 Lifestyle Factors
- Exercise Habits: High / Medium / Low  
- Smoking: Yes / No  
- Alcohol Consumption: High / Medium / Low  
- Stress Level: High / Medium / Low  
- Sleep Hours  
- Sugar Consumption: High / Medium / Low  

### 🧪 Blood Markers & Lab Results
- Triglyceride Level: 100–400 mg/dL  
- Fasting Blood Sugar: 80–160 mg/dL  
- CRP Level  
- Homocysteine Level  
- Low HDL Cholesterol: Yes / No  
- High LDL Cholesterol: Yes / No  

### 🎯 Target Variable
- Heart Disease Status: Yes / No  

---

## 🛠️ Data Preprocessing

- Loaded dataset from CSV  
- Checked data types and statistics  
- Handled missing values  
- Encoded categorical features  
- Cleaned `Unknown` values  
- Final dataset contains **no missing values**

**Missing Value Strategy**
- Numerical → Mean  
- Categorical → Mode  

---

## 📊 Data Visualization
- Age distribution histogram  
- Feature analysis plots  

---

## 🤖 Machine Learning Models
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)  
- Neural Networks  

---

## 📈 Model Evaluation
- Train-Test Split  
- Cross Validation  
- Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC
- Confusion Matrix

---

## 🚀 Future Enhancements
- Hyperparameter tuning  
- Feature importance analysis  
- SHAP / LIME  
- Streamlit web app  
- Model deployment as API  

---

## 📁 Project Structure

Heart-Disease-Prediction/
│
├── data/
│   └── heart_disease.csv
├── notebooks/
│   └── analysis.ipynb
├── models/
│   └── model.pkl
├── app.py
├── requirements.txt
└── README.md

---

## 👤 Author

**Kamran Ali**  
- Email: kamranali0844@gmail.com  
- WhatsApp: https://wa.me/923020813289  

---

## 📄 License
MIT License

---

## 🤝 Contributing
Contributions and feature requests are welcome!
