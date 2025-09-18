# California House Price Prediction 🏠

Predict California housing prices using **Machine Learning Regression models** with Python.  
This project compares the performance of **Random Forest Regressor** and **XGBoost Regressor** to accurately estimate house prices.

---

## 🔍 Project Overview

The goal of this project is to **predict median house values** in California using various features such as:
- Median income
- Number of rooms, bedrooms, households
- Population density
- Proximity to the ocean

We also **engineered new features** to improve model performance:
- `rooms_per_bedroom`: ratio of total rooms to bedrooms  
- `bedrooms_per_people`: number of bedrooms per person  
- `median_income_per_people`: median household income per person  
- `total_rooms_per_household`: number of rooms per person in households  

---

## 🛠️ Tools & Libraries

- **Python**  
- **Pandas / NumPy** for data manipulation  
- **Scikit-learn** for RandomForestRegressor and evaluation metrics  
- **XGBoost** for gradient boosting model  
- **Matplotlib / Seaborn** for data visualization  

---

## 📊 Models

We implemented and compared two regression models:

| Model                  | Description                                           |
|------------------------|-------------------------------------------------------|
| Random Forest Regressor| Ensemble model using multiple decision trees         |
| XGBoost Regressor      | Gradient boosting model for improved accuracy       |

### Evaluation Metrics:
- **R² Score**  
- **Mean Absolute Error (MAE)**  

We also visualized **predicted vs actual house values** and **feature correlations** to analyze model performance.

---

## 🚀 How to Run

1. Clone the repository:  
```bash
git clone https://github.com/yourusername/California_House_Price_Regression.git
