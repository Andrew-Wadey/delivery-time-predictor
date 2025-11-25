# 🚚 Delivery ETA Prediction Tool
AI-Powered Estimated Time of Arrival for Small & Medium Logistics Operators

This project demonstrates a complete end-to-end AI solution for predicting delivery times based on logistics features such as distance, weather, package characteristics, and time of day.
Built as a quick but realistic MVP, it shows your ability to deliver practical AI value to SMEs—especially those in logistics, transport, and delivery services.

---

### 🎯 Why This Project

Small and mid-sized logistics companies often give broad delivery windows (“1–5 days”) due to lack of prediction models.
This tool solves that by providing precise ETA predictions using machine learning.

---

### ✨ Business impact:

More accurate delivery estimates for customers

Better route planning and scheduling

Improved communication and SLA management

Reduced support tickets (“Where’s my package?”)

Creates a foundation for future optimization (routing, capacity planning, pricing)

---

### 🧠 What the Model Predicts

Given simple inputs, the tool predicts Estimated Time of Arrival (in hours/days) based on:

Origin → Destination distance

Time of day

Day of week

Traffic index

Weather conditions

Package weight & category

This keeps the model simple enough to explain, while still valuable to showcase applied AI.

---

### 🏗️ Project Structure

.
├── data/               # Raw & processed data files
├── notebooks/          # Jupyter notebooks for exploration & model training
├── model/              # Saved ML model (.joblib) and preprocessing pipeline
├── app/                # Streamlit app frontend
├── requirements.txt    # Python dependencies
└── README.md

---

### 🚀 Features

✔ Machine Learning Model

Trained using scikit-learn

Includes preprocessing (encoding, scaling)

Saved as a .joblib file for production use

Designed to be swapped with a real dataset later

✔ Streamlit Web App

Simple UI where you enter shipment details and receive a predicted ETA.

✔ Easy Deployment

Can be run locally or deployed on Streamlit Cloud / Hugging Face Spaces.

---

### ▶️ Quick Start
1. Install dependencies
pip install -r requirements.txt

2. Run the Streamlit App
streamlit run app/app.py

3. Predict ETA

Enter:

Origin & destination

Distance

Package weight

Weather

Time of day

Traffic index

…and receive an AI-generated ETA.

---

### 📊 Model Training

The notebook in notebooks/ includes:

EDA (distance, weather impact, traffic patterns)

Feature engineering

Train/test split

Model selection (Linear Regression / Random Forest)

Evaluation (MAE, RMSE)

Saving the final model

🔧 Tech Stack

Python 3.11

Pandas / NumPy

Scikit-Learn

Streamlit

Joblib

### 💼 Real-World Relevance

---

This MVP mirrors what SMEs actually need:

Fast setup

Lightweight infrastructure

Practical insights

Immediate business value

It’s also intentionally built to be extended:

Real API-driven weather & traffic data

Route optimization

Fleet assignment

Cost estimation

Delivery risk scoring

---

### 📬 Contact

Maintainer: Andrew Wade
Email: andrewwadeai@gmail.com
LinkedIn: www.linkedin.com/in/andrew-wade-1758-lewagon
