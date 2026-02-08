# ❤️Heart Disease Prediction Web App

A machine learning–based web application that predicts the risk of heart disease using patient health parameters.  
Built using **Python**, **Scikit-Learn**, and **Streamlit**.

---

## 🚀 Live Demo
👉 [(App Live link)](https://heart-disease-prediction-by-avni.streamlit.app/#heart-disease-prediction-by-avni))

---

## 📌 Features
- User-friendly Streamlit interface
- Logistic Regression ML model
- Real-time prediction
- Standardized input preprocessing
- One-hot encoded categorical features

---

## 🧠 Machine Learning Model
- Algorithm: **Logistic Regression**
- Data preprocessing:
  - One-hot encoding
  - Feature scaling using `StandardScaler`
- Target variable:
  - `1` → High risk of heart disease  
  - `0` → Low risk of heart disease

---

## 🛠 Tech Stack
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

### 🧪 Model Comparison Results

| Model               | Accuracy | F1-Score |
|--------------------|----------|----------|
| Logistic Regression | **89.67%** | **0.91** |
| K-Nearest Neighbors | 88.04%   | 0.8942   |
| Naive Bayes        | 88.04%   | 0.89     |
| Support Vector Machine (SVM) | 86.41% | 0.8815 |
| Decision Tree      | 75.00%   | 0.7723   |

Logistic Regression outperformed other models in terms of both accuracy and overall balance between precision and recall.

---

---

## 📊 Dataset Used
This project uses the **Heart Failure / Heart Disease Dataset** containing clinical parameters of patients such as age, blood pressure, cholesterol levels, ECG results, exercise-induced angina, and more.

The dataset includes both numerical and categorical features, which were preprocessed before model training.

---

## 🧪 Model Training & Evaluation
Multiple **supervised machine learning models** were trained and evaluated on this dataset, including:

- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  

After comparing model performance using accuracy as the evaluation metric, **Logistic Regression achieved the highest accuracy** and provided stable, reliable predictions.

Due to its strong performance and interpretability, Logistic Regression was selected as the final model for deployment.

---

## ⚙️ Data Preprocessing Steps
- Handling missing values
- One-hot encoding of categorical features
- Feature scaling using `StandardScaler`
- Train-test split for unbiased evaluation

The trained model, scaler, and expected feature columns were saved using `joblib` and integrated into the Streamlit application.


