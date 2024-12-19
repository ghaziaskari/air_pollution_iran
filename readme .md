Air Quality Prediction Project

Overview
This project aims to predict and classify air quality using machine learning techniques. We analyze the Air Quality Index (AQI) and its relationship with key pollutants using data from the Iranian Environmental Organization.

Dataset
2123 air pollution monitoring stations
Features: CO, O3, NO2, SO2, PM10, PM2.5
Target variables: AQI Average and AQI Description

Models
We implemented and compared several models for both regression and classification tasks:
Regression Models (AQI Average Prediction)
Gradient Boosting
XGBoost
Random Forest
KNN
Decision Tree
SVR
Linear Regression, Ridge, Lasso, ElasticNet

Classification Models (AQI Description)
KNN
XGBoost
Gradient Boosting
Random Forest
Decision Tree
SVC
Logistic Regression

Deep Learning
Multilayer Perceptron (MLP) for both regression and classification

Key Findings
Gradient Boosting performed best in both regression (MAE: 4.576557) and classification (Accuracy: 0.9426) tasks.
PM2.5 consistently emerged as the most important feature across all models.

Repository Structure
data/: Contains the dataset and preprocessed files
models/: Saved model files
notebooks/: Jupyter notebooks for data analysis and model development
src/: Source code for data preprocessing, model training, and evaluation
results/: Visualizations and result summaries

Getting Started
Clone the repository
Install required packages: pip install -r requirements.txt
Run the Jupyter notebooks in the notebooks/ directory for step-by-step analysis
Future Work
Incorporate meteorological factors
Develop regionalized models
Explore ensemble approaches combining Gradient Boosting and MLP
Contributors
Arman Ghaziaskari Naeini