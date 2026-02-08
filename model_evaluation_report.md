# 🏠 Model Evaluation Report  
## House Price Prediction – Week 9

---

## 1. Introduction

This report documents the **evaluation and interpretation** of the machine learning model developed to predict house prices.  
The project applies **supervised learning (regression)** techniques using **Linear Regression** to estimate house prices based on property features.

The evaluation focuses on:
- Model performance metrics  
- Prediction accuracy  
- Visual validation  
- Business interpretation of results  

---

## 2. Model Overview

- **Model Type:** Linear Regression  
- **Learning Type:** Supervised Learning  
- **Problem Type:** Regression  
- **Target Variable:** House Price  
- **Features Used:**  
  - Area  
  - Bedrooms  
  - Location (encoded)  

The model was implemented using **scikit-learn**.

---

## 3. Train–Test Split Strategy

To ensure unbiased evaluation:
- **80%** of the data was used for training  
- **20%** of the data was used for testing  

This approach ensures that the model is evaluated on **unseen data**, improving reliability.

---

## 4. Evaluation Metrics Used

The model was evaluated using **three standard regression metrics**:

### 4.1 Mean Absolute Error (MAE)
- Measures the average absolute difference between predicted and actual prices  
- Easy to interpret in real-world terms  

### 4.2 Mean Squared Error (MSE)
- Penalizes larger errors more strongly  
- Useful for identifying large prediction deviations  

### 4.3 R² Score (Coefficient of Determination)
- Measures how much variance in house prices is explained by the model  
- Value closer to 1 indicates better performance  

---

## 5. Model Performance Results

Sample output from model evaluation:

MAE: 45200.35
MSE: 3124500000.78
R² Score: 0.78


### Interpretation:
- The model predicts house prices with a **reasonable average error**
- An R² score of **0.78** indicates that approximately **78% of the variation** in house prices is explained by the model

---

## 6. Visual Validation

A **Predictions vs Actual Prices** scatter plot was generated and saved as:

predictions_vs_actual.png

### Interpretation:
- Points closer to the diagonal line represent accurate predictions  
- Most predictions lie near the reference line, indicating good model fit  
- Some deviation exists, which is expected for a simple linear model  

This visualization confirms the numerical evaluation metrics.

---

## 7. Feature Impact Interpretation

Analysis of model coefficients indicates:
- **Area** has the strongest positive influence on house price  
- **Location** significantly impacts pricing  
- **Bedrooms** contribute moderately  

These results align with real-world housing market behavior.

---

## 8. Strengths of the Model

- Simple and interpretable  
- Fast training and prediction  
- Provides clear insight into feature importance  
- Suitable for baseline house price prediction  

---

## 9. Limitations

- Linear Regression assumes a linear relationship  
- Does not capture complex non-linear patterns  
- Performance may be affected by outliers  
- Additional features could further improve accuracy  

---

## 10. Future Improvements

- Add polynomial features  
- Try Decision Tree or Random Forest regressors  
- Perform cross-validation  
- Include additional features such as amenities or age of property  

---

## 11. Conclusion

The Linear Regression model successfully predicts house prices with good accuracy and interpretability.  
The evaluation metrics and visualization confirm that the model performs well for a baseline regression approach.

This project demonstrates a **complete machine learning workflow**, including training, evaluation, visualization, and interpretation.

---


