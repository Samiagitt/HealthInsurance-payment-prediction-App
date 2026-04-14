
---

# 🏥 HEALTH INSURANCE PREDICTION 


## Overview

This project is a machine learning application that predicts insurance costs based on health and demographic data. It demonstrates regression modeling, feature scaling, and deployment using Streamlit.

---

## Objectives

- Predict insurance charges accurately  
- Analyze impact of health and lifestyle factors  
- Build a real-time prediction system  

---

## Dataset

- Insurance dataset with health and personal details  

---

## Data Processing Steps

- Feature scaling using StandardScaler  
- Encoding categorical variables  
- Data transformation  

---

## Model Details

- Model: Regression model  
- Input: Scaled + encoded features  
- Output: Predicted insurance cost  

---

## Features Used

- Age  
- Gender  
- BMI  
- Blood Pressure  
- Children  
- Diabetic Status  
- Smoking Status  

---

## Application Features

- Interactive Streamlit interface  
- Real-time predictions  
- Data preprocessing integration  
- Simple and clean UI  

---

## How It Works

User Input → Data Preprocessing → Model Prediction → Output  

---


🎯 Key Highlights

->Built a complete ML pipeline

->Integrated preprocessing + model in production

->Designed a user-friendly application

->Demonstrates real-world regression use case

---

🔮 Future Improvements

1.Add feature importance visualization

2.Improve UI design

3.Deploy on cloud

4.Add prediction explanation (SHAP)

---

## How to Run

```bash
git clone <repo-link>
cd insurance-app
pip install -r requirements.txt
streamlit run app.py
