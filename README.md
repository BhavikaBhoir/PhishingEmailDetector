# Phishing Email Detection System 🛡️

A machine learning–based web application that classifies emails as **phishing** or **legitimate** using advanced text processing and feature engineering techniques.

Built as a Final Year Project using Python, Scikit-learn, TF-IDF vectorization, and Streamlit.

---

## 🚀 Overview

Phishing emails are a major cybersecurity threat. This system analyzes email content, extracts multiple threat indicators, and uses a trained Logistic Regression model to accurately detect phishing attempts in real time.

The application is designed so that even non-technical users can analyze suspicious emails through a simple web interface.

---

## 🧠 Key Features

- Logistic Regression model trained with **TF-IDF** text vectorization
- 200+ engineered phishing indicators across 8 feature categories:
  - URL patterns
  - Header anomalies
  - Keyword density
  - Suspicious phrases
  - Formatting tricks
  - Domain irregularities
  - Link obfuscation
  - Content structure analysis
- Real-time prediction with **confidence score**
- Interactive **Streamlit** dashboard
- Automated **PDF threat report** generation for audit and reporting
- High precision and recall on benchmark phishing datasets

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Streamlit
- Pandas, NumPy

---

## 💡 Purpose

This project demonstrates how machine learning and cybersecurity concepts can be combined to build a practical phishing detection system usable by everyday users.

---

## 📁 Project Components

- ML model training and evaluation
- Feature engineering for phishing detection
- Streamlit web interface for user interaction
- PDF report generator for detected threats
