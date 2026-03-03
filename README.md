# Predicting-House-Prices-with-Linear-Regression-Machine-Learning-Project-


## Overview

This project builds a Linear Regression model to predict house prices based on property features.  
It follows a complete machine learning workflow including data preprocessing, feature encoding, scaling, model training, and evaluation.

The objective is to understand how different housing attributes influence price and measure model performance using regression metrics.

---

## Dataset

**File Used:** Housing.csv  

The dataset contains property-related features such as:

- area  
- bedrooms  
- bathrooms  
- stories  
- mainroad  
- guestroom  
- basement  
- hotwaterheating  
- airconditioning  
- parking  
- prefarea  
- furnishingstatus  
- price (Target Variable)

---

## Features and Target

**Input Features (X):**
- area
- bedrooms
- bathrooms
- stories
- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- parking
- prefarea
- furnishingstatus

**Target Variable (y):**
- price

---

## Project Workflow

1. Data loading using Pandas  
2. Data inspection and missing value handling  
3. Encoding categorical variables  
4. Feature scaling using StandardScaler  
5. Train-test split (80% training, 20% testing)  
6. Model training using Linear Regression  
7. Performance evaluation using:
   - R² Score
   - Mean Absolute Error (MAE)  
8. Visualization of Actual vs Predicted prices  

---

## Model Evaluation

The model performance is measured using:

- **R² Score** – Indicates how well the model explains price variation.
- **Mean Absolute Error (MAE)** – Measures average prediction error.

---

## Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## Key Learning Outcomes

- Understanding regression modeling  
- Handling categorical data  
- Preventing data leakage  
- Applying feature scaling  
- Evaluating regression models  

---

## Conclusion

The Linear Regression model demonstrates how housing characteristics influence price.  
This project showcases a complete machine learning pipeline applied to real-world structured data.
