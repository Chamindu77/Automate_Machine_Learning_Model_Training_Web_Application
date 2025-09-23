# Automate Machine Learning Model Training Web Application

This project is a **no-code machine learning model training web application** built with **Streamlit**.  
It allows users to easily upload datasets, preprocess data, select ML models, train them, and evaluate results — all from a simple web interface.

<img width="1088" height="761" alt="image" src="https://github.com/user-attachments/assets/45fac86e-0ee2-4865-b0cd-bb9a02ce646a" />


---

## 🚀 Features

- 📂 **Dataset Management**: Load CSV or Excel files from the `data/` directory.
- ⚙️ **Preprocessing**:
  - Handles missing values (numerical → mean imputation, categorical → mode imputation).
  - Scaling with **StandardScaler** or **MinMaxScaler**.
  - Automatic **One-Hot Encoding** for categorical features.
- 🧠 **Model Selection**:
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - Random Forest Classifier
  - XGBoost Classifier
- 🎯 **Model Training & Saving**:
  - Train ML models with a single click.
  - Save trained models automatically as `.pkl` files in the `trained_model/` directory.
- 📊 **Evaluation**:
  - Test accuracy displayed after training.
  - Data preview and selection of target column.

---
