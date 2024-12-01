https://mlprojpremiumprediction-healthcare.streamlit.app/
# ML_Premium_Prediction

## Health Insurance Premium Prediction App

### Overview

The **Health Insurance Premium Prediction App** is a machine learning application that predicts health insurance premiums based on various features such as age, income, and medical history. The app uses a combination of Linear Regression, Ridge Regression, and XGBoost models to provide accurate predictions. The front end is developed using **Streamlit**.

### Features

- **Data Preprocessing:** Cleans and prepares the data by handling missing values, outliers, and categorical features.
- **Model Training:** Trains Linear Regression, Ridge Regression, and XGBoost models.
- **Hyperparameter Tuning:** Uses RandomizedSearchCV for optimizing the XGBoost model.
- **Model Evaluation:** Evaluates models using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
- **Prediction:** Provides predictions based on user input through the Streamlit interface.

---

### Getting Started

#### Prerequisites

- **Python** 3.12 or higher
- **Pip** (Python package installer)

---

### File Structure

- `main.py`: Main Streamlit application script.
- `prediction_helper.py`: Contains functions for loading models and making predictions.
- `requirements.txt`: Lists all Python dependencies required for the project.
- `artifacts/model_rest.joblib`: Saved model file.
- `artifacts/scaler_rest.joblib`: Saved scaler file.
- `README.md`: This file.

---

### Contact

For any questions or issues, please contact:  
**Email:** kishoresj1807@gmail.com
