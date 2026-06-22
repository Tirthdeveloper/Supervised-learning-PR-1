# House Price Prediction using Supervised Learning

##  Project Overview

This project demonstrates the implementation and evaluation of multiple Supervised Learning algorithms for predicting house prices. The objective is to analyze the impact of different property features on house prices and compare the performance of various regression models.

The project covers the complete Machine Learning workflow including data understanding, visualization, model building, evaluation, gradient descent concepts, and bias-variance analysis.

---

## Problem Statement

A real estate analytics firm wants to build a predictive system to estimate house prices based on property characteristics such as:

- House Area
- Number of Bedrooms
- Number of Bathrooms
- Location Score
- Property Age
- Distance from City
- Lot Size
- Garage Availability
- Swimming Pool Availability
- Renovation History

The goal is to develop and evaluate multiple regression models and determine which model predicts house prices most accurately.

---

## Dataset Information

### Features

| Feature | Description |
|----------|-------------|
| house_id | Unique house identifier |
| area_sqft | House area in square feet |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| location_score | Location quality score |
| age_years | Age of property |
| distance_city_km | Distance from city center |
| lot_size_sqft | Total lot size |
| has_garage | Garage availability |
| has_pool | Swimming pool availability |
| renovation_years_ago | Years since last renovation |
| house_price_inr | Target variable |

### Target Variable

- **house_price_inr**

---

# Part A: Conceptual Understanding

Covered theoretical concepts:

- Supervised Learning
- Regression vs Classification
- Simple Linear Regression
- Linear Regression Assumptions
- Bias-Variance Tradeoff
- Overfitting and Underfitting

---

# Part B: Dataset Understanding & Preparation

Performed:

- Dataset loading
- Dataset exploration
- Missing value analysis
- Correlation analysis
- Feature-target relationship visualization
- Train-test splitting

### Visualizations

- Correlation Heatmap
- Area vs House Price Scatter Plot
- Location Score vs House Price Scatter Plot
- Pair Plot Analysis

---

# Part C: Simple Linear Regression

Implemented Simple Linear Regression using:

- area_sqft → Independent Variable
- house_price_inr → Dependent Variable

### Outputs

- Regression Line
- Slope
- Intercept
- Residual Analysis

---

# Part D: Model Evaluation Metrics

Evaluated the model using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R² Score

---

# Part E: Multiple Linear Regression

Implemented Multiple Linear Regression using all relevant features.

### Objective

To compare the performance of:

- Simple Linear Regression
- Multiple Linear Regression

---

# Part F: Polynomial Regression

Implemented Polynomial Regression (Degree = 2).

### Analysis

- Linear vs Polynomial Comparison
- Performance Evaluation
- Overfitting and Underfitting Detection

---

# Part G: Gradient Descent Optimization

Studied and implemented:

### Batch Gradient Descent

Uses the entire dataset for each update.

### Stochastic Gradient Descent (SGD)

Uses one training sample at a time.

### Mini-Batch Gradient Descent

Uses small batches of data for optimization.

### Comparison

- Convergence Speed
- Stability
- Computational Efficiency

---

# Part H: Bias-Variance Analysis

Compared:

- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression

### Evaluation Factors

- Bias
- Variance
- Generalization Ability

---

# Part I: Final Analysis

The project concludes with:

- Best Performing Model
- Model Comparison
- Gradient Descent Insights
- Overfitting/Underfitting Analysis
- Business Interpretation

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab / Jupyter Notebook

---

# Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

# How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook or Google Colab

4. Run:

```bash
Supervised_Learning_pr1.ipynb
```

---

# Results Summary

- Simple Linear Regression established a baseline model.
- Multiple Linear Regression improved prediction accuracy by utilizing multiple features.
- Polynomial Regression captured non-linear relationships and achieved better performance.
- Gradient Descent methods demonstrated different optimization behaviors.
- Bias-Variance analysis helped identify the most balanced model.

---

# Learning Outcomes

Through this project, the following concepts were explored:

- Data Preprocessing
- Data Visualization
- Linear Regression
- Polynomial Regression
- Model Evaluation Metrics
- Gradient Descent Optimization
- Bias-Variance Tradeoff
- Predictive Analytics

---

# Author

**Tirth Patel**

Machine Learning & Data Science Enthusiast

---
