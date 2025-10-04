# 📦 E-commerce Delivery Time Prediction

Predicting whether online orders will be delivered on time using machine learning — a data-driven approach to improving logistics and customer satisfaction for an international electronics store.

---


## 📘 Project Overview

In today’s competitive e-commerce landscape, **delivery speed** is critical for customer retention and business success. This project leverages machine learning to predict whether an order will be **delivered on time**, helping companies:

- Reduce logistics costs
- Identify at-risk orders before shipping
- Enhance overall customer experience
- Detailed analysis in notebook

---

## 📊 Dataset Summary

The dataset contains **10,999 transactions** with the following features:

- 📦 Warehouse block (A–E)
- 🚚 Mode of shipment (Ship, Flight, Road)
- 📞 Customer care calls
- ⭐ Customer rating (1–5)
- 💰 Cost of product
- 🔁 Prior purchases
- 🔥 Product importance (Low, Medium, High)
- ⚖️ Weight in grams
- 🎯 **Target**: `Reached on time` (1 = Late, 0 = On Time)

---

## 🧠 Project Goals

- Build a binary classification model to predict late deliveries.
- Analyze key business drivers (e.g., discounts, weight).
- Translate insights into logistics improvements.
- Save the best model for deployment.
- The trained model (`best_model.pkl`) is included for easy reuse and deployment.

---

## 🧪 Tools & Libraries Used

- **Python**
- `pandas`, `numpy` for data wrangling  
- `matplotlib`, `seaborn` for visualization  
- `scikit-learn`, `xgboost`, `lightgbm`, `catboost` for modeling  
- `imbalanced-learn` to handle class imbalance  
- `pickle` for model saving  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-delivery-prediction.git
   cd ecommerce-delivery-prediction
   ```

## 📄 License
MIT

---

## 🗣️ Author
Hakim Murphy
