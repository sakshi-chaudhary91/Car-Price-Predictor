# 🚗 Car Price Prediction Model

A machine learning project built with Python and Scikit-Learn to predict the selling price of used cars based on various attributes like present showroom price, kilometers driven, fuel type, transmission, and seller type.

---

## 📋 Project Overview
Buying and selling used cars can be tricky when determining the right price. This project builds a **Linear Regression** model to accurately estimate the market value of a used car, helping buyers and sellers make data-driven decisions.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Linear Regression, Train-Test Split, Metrics)

---

## ⚙️ Project Workflow
1. **Data Preprocessing & Cleaning:** Handled missing values, removed duplicates, and prepared the dataset.
2. **Categorical Encoding:** Converted categorical text columns (`Fuel_Type`, `Seller_Type`, `Transmission`) into numerical format using One-Hot Encoding (`pd.get_dummies`).
3. **Train-Test Split:** Split the dataset into 80% training data and 20% testing data.
4. **Model Training:** Trained a Linear Regression model using `scikit-learn`.
5. **Evaluation:** Evaluated model performance using **R² Score** (achieved ~75% accuracy) and **Mean Absolute Error (MAE)**.
6. **Visualization:** Plotted an *Actual vs Predicted Prices* scatter plot to visualize model accuracy.

---

## 📊 Results & Evaluation
* **R² Score:** ~0.7528
* **Mean Absolute Error:** 1.472892414003326
* The model successfully captures the linear relationships between showroom prices, kilometers driven, and final selling prices.

---

