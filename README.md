# 🚗 Car Purchase Amount Prediction using Deep Learning

## 📌 Project Overview

This project aims to predict the **car purchase amount** a customer is likely to spend based on demographic and financial attributes. The model is built using an Artificial Neural Network (ANN) to capture complex relationships between features.

---

## 🎯 Problem Statement

Given customer attributes such as age, gender, salary, debt, and net worth, the objective is to build a machine learning model that predicts the **total amount a customer is willing to spend on a car**.

---

## 📊 Dataset Description

The dataset contains the following features:

* Customer Name *(removed during preprocessing)*
* Customer Email *(removed during preprocessing)*
* Country *(removed during preprocessing)*
* Gender
* Age
* Annual Salary
* Credit Card Debt
* Net Worth

🎯 Target Variable:

* **Car Purchase Amount**

---

## ⚙️ Approach

### 1. Data Preprocessing

* Removed irrelevant columns (Name, Email, Country)
* Feature scaling using MinMaxScaler

### 2. Model Building

* Built an Artificial Neural Network using Keras
* Architecture:

  * Input Layer
  * 2 Hidden Layers (ReLU activation)
  * Output Layer (Linear activation)

### 3. Model Training

* Loss Function: Mean Squared Error
* Optimizer: Adam
* Train-Test Split: 75%-25%

### 4. Evaluation

* Visualized training and validation loss
* Calculated RMSE for performance evaluation

---

## 📈 Results

The model successfully learns patterns in customer financial behavior and predicts purchase amounts with reasonable accuracy.

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```
   colab notebook
   ```

---

## 💡 Future Improvements

* Try other models (Linear Regression, XGBoost)
* Hyperparameter tuning
* Deploy using Flask/Streamlit

---

## 👨‍💻 Author

Prakriti Anand
