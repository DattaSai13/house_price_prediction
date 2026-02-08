# 🏠 Week 9 – House Price Prediction using Machine Learning

## 📌 Project Overview

This project is part of **Week 9: Introduction to Machine Learning Concepts**.  
The objective is to build a **supervised machine learning regression model** to predict **house prices** based on property features such as area, number of bedrooms, and location.

The project demonstrates the **complete machine learning workflow**, including:
- Data preprocessing
- Model training
- Evaluation
- Visualization
- Interpretation of results

---

## 🎯 Project Objectives

- Understand the basics of Machine Learning
- Implement Linear Regression for price prediction
- Perform proper train-test split
- Evaluate model performance using multiple metrics
- Visualize predicted vs actual house prices
- Document model performance and insights

---


House_Price_Prediction/
│
├── house_price_prediction.ipynb
├── house_prices.csv
├── model_evaluation_report.md
├── predictions_vs_actual.png
├── requirements.txt
└── README.md


---

## 📊 Dataset Description

### `house_prices.csv`
This dataset contains information about houses and their selling prices.

Typical columns include:
- `Area`
- `Bedrooms`
- `Location`
- `Price` (Target Variable)

---

## ⚙️ Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning model implementation

---

## 🧠 Machine Learning Approach

### Problem Type
- **Supervised Learning**
- **Regression Problem**

### Model Used
- **Linear Regression**

### Workflow
1. Load and explore the dataset
2. Handle missing values
3. Encode categorical variables
4. Split data into training and testing sets
5. Train Linear Regression model
6. Evaluate model using standard metrics
7. Visualize predictions vs actual values

---

## 📈 Model Evaluation

The model performance is evaluated using the following metrics:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

Sample output:
MAE: 45200.35
MSE: 3124500000.78
R² Score: 0.78


---

## 📉 Visualization

A scatter plot comparing **Actual vs Predicted House Prices** is created to visually assess model performance.

- File saved as: `predictions_vs_actual.png`
- Points close to the diagonal line indicate accurate predictions

---

## 🧪 Testing & Validation

- Data is split into training and testing sets (80:20)
- Model is evaluated on unseen test data
- Performance metrics and visualizations validate results

---

## 💡 Key Insights

- Area has the strongest impact on house prices
- Location significantly affects pricing
- Bedrooms contribute moderately
- Linear Regression explains a large portion of price variance

---

## ⚠️ Limitations

- Linear Regression assumes linear relationships
- Does not capture complex non-linear patterns
- Model performance may vary with additional features

---

## 🚀 Future Enhancements

- Add polynomial features
- Implement Decision Tree or Random Forest models
- Perform cross-validation
- Include more property features

---

## ▶️ Setup Instructions

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt

2️⃣ Run the Notebook

Open and execute:

house_price_prediction.ipynb
## 📁 Project Structure

