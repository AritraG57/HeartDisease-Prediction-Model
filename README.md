# ❤️ Heart Stroke Prediction Web App (Streamlit)

## 📖 Project Description
This project is a **Machine Learning–based web application** built using **Streamlit** that predicts the **risk of heart disease/stroke** from user health inputs.  
It uses a **KNN (K-Nearest Neighbors)** model and provides instant predictions through an interactive UI.

---

## 🎯 Objective
To help users quickly assess their **heart disease risk** by entering basic medical information.

---

## 🧠 Machine Learning Model
- **Algorithm:** K-Nearest Neighbors (KNN)
- **Preprocessing:**
  - One-hot encoding for categorical features
  - Feature scaling using `StandardScaler`
- **Saved Files:**
  - `knn_heart.pkl` → trained model
  - `scaler.pkl` → fitted scaler
  - `columns.pkl` → expected feature columns

---

## 🖥️ Application Features
- Interactive sliders and dropdowns
- Real-time prediction
- Clear result display:
  - ⚠️ High Risk
  - ✅ Low Risk

---

## 📊 Input Parameters
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

---

## 🛠️ Technologies Used
- Python
- Streamlit
- Pandas
- Scikit-learn
- Joblib
- Matplotlib
- Seaborn
- Numpy

---

## 📂 Project Structure
├── app.py
├── knn_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
└──README.md
---

## ▶️ How to Run the Application

### 1. Install dependencies
```bash
pip install streamlit pandas scikit-learn joblib

2. Run the app
streamlit run app.py

3. Open in browser
http://localhost:8501

📈 Output

High Risk of Heart Disease → shown in red

Low Risk of Heart Disease → shown in green

📌 Disclaimer

This project is for educational purposes only and should not be used for medical diagnosis.

👨‍💻 Author

Aritra
