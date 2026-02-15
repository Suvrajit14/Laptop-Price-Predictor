# 💻 Laptop Price Predictor

## 📌 Project Overview
This project aims to predict the price of laptops based on their hardware specifications and brand information using Machine Learning regression techniques.

## 🎯 Objective
To develop a predictive model that estimates laptop prices using features such as RAM, processor, display size, storage type, and other technical specifications.

## 📊 Dataset
- Source: Kaggle Laptop Price Dataset
- Total Records: 893
- Features include:
  - Brand
  - Processor
  - RAM
  - Storage (ROM)
  - GPU
  - Display Size
  - Resolution
  - Operating System
  - Warranty

## 🧠 Machine Learning Models Used
- Linear Regression
- Random Forest Regressor

## 📈 Model Performance
- Linear Regression R² Score: ~0.82
- Random Forest R² Score: ~0.83
- Mean Absolute Error (MAE): ~13,000

## 🔎 Key Insights
- RAM and processor type significantly influence laptop pricing.
- Brand and display specifications also contribute to price variation.
- Random Forest slightly outperformed Linear Regression.

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 🚀 Conclusion
The project successfully demonstrates how regression models can be applied to predict laptop prices with good accuracy. Random Forest provided better generalization compared to Linear Regression.
