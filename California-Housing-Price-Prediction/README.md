California Housing Price Prediction

A Machine Learning project for predicting California housing prices using preprocessing pipelines, feature engineering, and regression models in Scikit-learn.

Project Overview

This project focuses on building a complete Machine Learning workflow for predicting median house values in California districts using the California Housing dataset.

The project includes:

Exploratory Data Analysis (EDA)
Data preprocessing
Handling missing values
Feature scaling
Categorical encoding
Building ML pipelines
Training multiple regression models
Hyperparameter tuning using GridSearchCV
Model evaluation using RMSE
Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Dataset

The project uses the California Housing dataset.

Features include:

Median income
Housing median age
Total rooms
Population
Households
Latitude & longitude
Ocean proximity

Target variable:

Median house value
Project Workflow
1. Data Exploration
Checked dataset structure using info() and describe()
Visualized distributions using histograms
Analyzed feature correlations
2. Data Preprocessing
Handled missing values using SimpleImputer
Scaled numerical features using StandardScaler
Encoded categorical features using OneHotEncoder
Built preprocessing pipelines using:
Pipeline
ColumnTransformer
3. Model Training

Implemented and trained:

Support Vector Regressor (SVR)
Random Forest Regressor
4. Hyperparameter Tuning

Used GridSearchCV to optimize model performance.

5. Evaluation

Models were evaluated using:

Root Mean Squared Error (RMSE)
Results

The Random Forest model achieved better performance compared to SVR after hyperparameter tunin



Future Improvements
Add feature engineering
Save trained models using Joblib
Deploy the model using Flask or FastAPI
Try advanced boosting models such as XGBoost
Build an interactive web application
