# 🏠 California Housing Price Prediction

This project is a machine learning pipeline for predicting **median house values** in California districts using the popular **California Housing Dataset**.

## 📊 Dataset
- Source: [Hands-On ML 2 GitHub](https://github.com/ageron/handson-ml2)
- Includes features such as: total rooms, population, households, ocean proximity, etc.

## 🔧 What the project does
- Loads and explores the housing dataset
- Splits data into training and test sets
- Performs feature engineering:
  - Adds `rooms_per_household`, `population_per_household`, and optionally `bedrooms_per_room`
- Handles missing values using median imputation
- Applies standard scaling to numerical attributes
- Encodes categorical features using OneHotEncoder
- Combines all transformations into a clean pipeline using `Pipeline` and `ColumnTransformer`

## 🧠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn (`Pipeline`, `SimpleImputer`, `StandardScaler`, `OneHotEncoder`)
- Custom transformer using `BaseEstimator` and `TransformerMixin`

## 🚀 How to run
1. Clone the repository  
2. Run the notebook or script (`.ipynb` or `.py`)  
3. All preprocessing is handled via pipelines – ready for model training!

## 📁 Folder structure
