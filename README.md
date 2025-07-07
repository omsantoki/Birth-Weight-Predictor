# 🍼 Birth Weight Predictor

A machine learning project that predicts a newborn's birth weight using maternal health and pregnancy-related data.

---

## 🔍 Overview

This project aims to estimate the **birth weight of a child** (in ounces) using multiple features such as gestation period, mother’s age, height, weight, and smoking habits.

### 🔧 Technologies Used

- **Python 3.11**  
- **Pandas, NumPy, Matplotlib, Seaborn** – for data preprocessing and EDA  
- **Scikit-learn** – model building and evaluation  
- **Pickle** – for model serialization  
- **REST API** – for client-server communication   
- **Render** – for deployment 

## 🚀 Live Demo

The project is deployed on **Render**:

🌐 [https://birth-weight-predictor-cloq.onrender.com](https://birth-weight-predictor-cloq.onrender.com)

---

## 🔁 ML API Overview

- Endpoint accepts JSON input and returns a predicted birth weight  
- Ideal for use in mobile/web apps or hospital systems

---

## 📦 API Usage

**Endpoint**: `/predict`  
**Method**: `POST`  

### 🔽 Input Example:
```json
{
  "gestation": 284,
  "parity": 0,
  "age": 27,
  "height": 62,
  "weight": 135,
  "smoke": 1
}
