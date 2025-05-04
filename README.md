# 🏠 House Price Prediction: Basic Model Comparison

![House Price Prediction Banner](https://github.com/alphaaa-m/House_Price_Prediction-Basic/raw/main/House_Price_Prediction_Cover.png)

## 🔍 Introduction

This project focuses on predicting house prices by leveraging key features such as area, bedrooms, bathrooms, and location. It implements and compares a diverse set of regression models to evaluate their predictive performance on the given dataset.

### 🔑 Key Steps:

- **Data Loading & Exploration**: Load dataset and perform EDA.
- **Data Preprocessing**: Clean and prepare data for modeling.
- **Model Implementation**: Implement a variety of regression models.
- **Train & Evaluate Models**: Compare performance on key metrics.

---

## ⚙️ Implemented Models

### 🔹 Linear Models:
- Linear Regression  
- Lasso Regression  
- Ridge Regression  
- ElasticNet Regression  

### 🔸 Non-linear Models:
- Polynomial Regression (degree = 2)  
- Support Vector Regression (SVR)  

### 🌲 Tree-Based Models:
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  

---

## 📊 Performance Comparison

All models were evaluated using:

- **R² Score**  
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **Mean Absolute Percentage Error (MAPE)**  

---

## ✅ Model Performance Summary

### ⭐ Top Performers
| Model                 | R² Score | MAE     | MSE      | Key Strength               |
|-----------------------|----------|---------|----------|----------------------------|
| Gradient Boosting     | 0.993    | 10,091  | 165M     | **Lowest MAE**             |
| Random Forest         | 0.992    | 10,402  | 174M     | Best balanced performance  |
| Polynomial Regression | 0.996    | 7,512   | 88.6M    | Highest R² (check overfit) |

### 🔄 Mid-Range Models
| Model           | R² Score | MAE     | MSE      | Notes                      |
|-----------------|----------|---------|----------|----------------------------|
| ElasticNet      | 0.963    | 21,652  | 835M     | Good regularization        |
| Linear          | 0.980    | 16,683  | 458M     | Baseline performance       |
| Lasso           | 0.980    | 16,683  | 458M     | Similar to Linear          |
| Ridge           | 0.980    | 16,700  | 458M     | Similar to Linear          |

### ⚠️ Underperformers
| Model          | R² Score | MAE     | MSE      | Issues                     |
|----------------|----------|---------|----------|----------------------------|
| Decision Tree  | 0.985    | 14,042  | 341M     | Prone to overfitting       |
| SVR (Linear)   | 0.789    | 55,438  | 4.74B    | Needs feature scaling      |

---

## 🧠 Key Insights

1. **Tree-Based Models Excel**  
   - Gradient Boosting and Random Forest provide superior accuracy.  
   - Effective in capturing non-linear relationships.

2. **Linear Models Are Limited**  
   - Useful for baseline comparisons.  
   - ElasticNet stands out with balanced regularization.

3. **Model-Specific Cautions**  
   - Polynomial Regression shows high R² but risks overfitting.  
   - SVR demands proper feature scaling and kernel tuning.

---

## 🔮 Future Work

- 🔧 **Hyperparameter tuning** (GridSearchCV / RandomizedSearchCV)  
- 🔍 **Advanced feature engineering**  
- 🔁 **Cross-validation techniques**  
- 🚀 **Model deployment for real-world usage**

---


## 👨‍💻 Author

**Muneeb Ashraf**  
_Stepping stone for advanced ML projects._ 

---

## 📢 Connect with Me

Feel free to connect for collaborations, feedback, or suggestions!

🔗 **GitHub Repo Link**: [Visit Here](https://github.com/alphaaa-m/House_Price_Prediction-Basic)

---
