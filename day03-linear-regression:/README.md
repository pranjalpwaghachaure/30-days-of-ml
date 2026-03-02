# 🏠 House Price Prediction --- Linear Regression

## 📌 Problem Statement

Predict housing-related target values using Linear Regression.

## 📊 Dataset

Built-in sklearn dataset (offline compatible)

## 🛠 Model Used

-   StandardScaler
-   Linear Regression

## 📈 Evaluation Metric

-   R² Score

## ✅ Model Performance

R² Score on Test Set: 0.4526

## 🚀 How to Use

``` python
import pickle

with open("model.pkl", "rb") as f:
    model = pickle.load(f)

sample_input = [[0.0380759, 0.0506801, 0.0616962, 0.0218724, -0.0442235, -0.0348208, -0.0434008, -0.0025923, 0.0199075, -0.0176461]]
prediction = model.predict(sample_input)
print(prediction)
```

## 📁 Project Structure

day03-linear-regression/ │── house_price.ipynb\
│── model.pkl\
│── README.md

------------------------------------------------------------------------

Built as part of the 30 Days of ML Roadmap 🚀
