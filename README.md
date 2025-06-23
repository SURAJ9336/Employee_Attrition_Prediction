# 🧠 Employee Attrition Prediction App

A machine learning-powered web app that predicts whether an employee is likely to leave the company based on their profile data. Built with Streamlit for an interactive frontend and trained on IBM's HR Analytics Attrition dataset using a Random Forest Classifier.

---

## 🚀 Live Demo

📍 Deployment link
https://employee-leave-predictor.streamlit.app/

---

## 📌 Key Features

✅ Predicts employee attrition (Leave/Stay)  
✅ Simple form-based UI using Streamlit  
✅ Model trained on real HR attrition dataset  
✅ Displays prediction confidence (%)  
✅ Binary & One-Hot Encoding for categorical features  
✅ Ready for interviews, demo, and deployment

---

## 🧠 Tech Stack

| Component      | Tech Used                |
|----------------|--------------------------|
| Frontend       | Streamlit                |
| Backend/Logic  | Python, scikit-learn     |
| ML Model       | RandomForestClassifier   |
| Data           | IBM HR Attrition Dataset |
| Visualization  | Matplotlib (optional)    |

---

## 📁 Project Structure

employee_attrition_app/
│
├── app.py # Main Streamlit app
├── WA_Fn-UseC_-HR-Employee-Attrition.csv # HR dataset
├── requirements.txt # Required Python packages
├── .gitignore # Files to ignore
└── README.md # Project documentation


---

## 📂 Dataset Summary

- Source: IBM HR Analytics Employee Attrition & Performance dataset
- Total Features: 35+
- Target Variable: `Attrition` (Yes/No → 1/0)
- Includes: Age, Gender, Job Role, OverTime, Monthly Income, YearsAtCompany, etc.

---

## 🛠 How to Run Locally

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/employee-attrition-app.git
cd employee-attrition-app


2. Install dependencies

pip install -r requirements.txt

3. Launch the Streamlit app

streamlit run app.py


🔍 Model Insights
Used RandomForestClassifier from scikit-learn

80/20 train-test split for evaluation

Feature importance used to understand key attrition factors

Binary & one-hot encoding applied to clean categorical variables


📦 Future Improvements
 Upload CSV for batch employee predictions

 Add SHAP explainability

 Deploy on Hugging Face / Render

 Add download button for result



 🧑‍💼 Use Cases
HR Attrition Analysis

Talent Management Strategy

Live Demo in Interviews

Resume + GitHub Portfolio Project



📄 Author
Suraj Kumar


⚠️ License
This project is open-source and for educational/demo purposes only.
