# 🚚 Delivery ETA Prediction Tool

### AI-Powered Estimated Time of Arrival for Small & Medium Logistics Operators

This project demonstrates a complete end-to-end AI solution for predicting delivery times based on logistics features such as distance, weather, package characteristics, and time of day.  
Built as a quick MVP, it shows applied AI value for SMEs in logistics, transport, and delivery services.

---

## 🎯 Why This Project

Small and mid-sized logistics companies often give broad delivery windows (“1–5 days”) due to lack of prediction models.  
This tool provides **precise ETA predictions** using machine learning.

### ✨ Business Impact

- Accurate delivery estimates for customers  
- Better route planning and scheduling  
- Improved communication and SLA management  
- Reduced support inquiries  
- Foundation for future optimization (routing, capacity planning, pricing)

---

## 🧠 What the Model Predicts

Given inputs, the tool predicts **Estimated Time of Arrival (ETA)** based on:

- Distance between origin and destination  
- Time of day & day of week  
- Traffic index  
- Weather conditions  
- Package weight & category

---

## 🏗️ Project Structure

```text
.
├── data/               # Raw & processed data files
├── notebooks/          # Jupyter notebooks for exploration & model training
├── model/              # Saved ML model (.joblib) and preprocessing pipeline
├── app/                # Streamlit app frontend
├── requirements.txt    # Python dependencies
└── README.md
```
---

## 🚀 Features

✔ Machine Learning Model

- Preprocessing + training pipeline
  
- Baseline Random Forest / Gradient Boosting

- Saved as .joblib for inference

✔ Streamlit Web App

- Simple UI for entering shipment details

- Predicts ETA with confidence estimate

✔ Easy Deployment

- Run locally or deploy to Streamlit Cloud / Hugging Face Spaces

---

## ▶️ Quick Start

1. Install dependencies
```
bash
Copy code
pip install -r requirements.txt
```
2. Run the Streamlit App
```
bash
Copy code
streamlit run app/app.py
```
3. Predict ETA
   
Enter shipment details:

- Origin & destination

- Distance

- Package weight

- Weather

- Time of day

- Traffic index

…and receive an AI-generated ETA.

---

## 📊 Model Training

The notebook in /notebooks includes:

- Data cleaning and preprocessing

- Feature engineering

- Train/test split

- Model training & evaluation (MAE, RMSE)

- Saving the final model

---

## 🔧 Tech Stack

- Python 3.10+

- Pandas / NumPy

- Scikit-Learn

- Streamlit

- Joblib

---

## 📬 Contact

Maintainer: Andrew Wade

Email: andrewwadeai@gmail.com

LinkedIn: www.linkedin.com/in/andrew-wade-1758-lewagon
