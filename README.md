# Fuel Consumption Regression Models

This project explores multiple regression models to predict vehicle carbon dioxide emissions (`CO2EMISSIONS`) based on fuel consumption and vehicle-related features.

The notebook compares different approaches, including:
- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Random Forest Regression

Among the tested models, **Random Forest Regression** achieved the best performance.

---

## Project Overview

The goal of this project is to build predictive models that estimate `CO2EMISSIONS` using vehicle characteristics such as engine size, fuel type, vehicle class, and transmission type.

This notebook includes:
- Data preprocessing
- Categorical feature encoding
- Correlation analysis
- Train/test splitting
- Model training
- Model evaluation
- Model comparison

---

## Dataset

The dataset contains information about vehicle fuel consumption and emissions.  
Important features used in this project include:

- `ENGINESIZE`
- `CYLINDERS`
- `FUELTYPE`
- `VEHICLECLASS`
- `TRANSMISSION`
- `CO2EMISSIONS` as the target variable

---

## Preprocessing

To prepare the data for machine learning:
- Categorical features were encoded using `LabelEncoder`
- Correlation analysis was performed using a heatmap
- The dataset was split into training and testing sets

---

## Models Used

### 1. Simple Linear Regression
A baseline model used to predict `CO2EMISSIONS` using a single feature.

### 2. Multiple Linear Regression
A model that uses several features to improve prediction accuracy.

### 3. Polynomial Regression
A 2nd-degree polynomial model was used to capture non-linear relationships in the data.

### 4. Random Forest Regression
An ensemble-based model that combines multiple decision trees.  
This model produced the best score and performed better than the linear-based approaches.

---

## Evaluation Metrics

The models were evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

These metrics were used to compare the predictive performance of each model.

---

## Results

After comparing all models, **Random Forest Regression** gave the highest performance score on the test set.  
This suggests that the relationship between the input features and `CO2EMISSIONS` is complex and non-linear.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/python-is-life2022/Fuel-Consumption-Regression-Models.git
