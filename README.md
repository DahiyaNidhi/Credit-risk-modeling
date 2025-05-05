# Credit Risk Modeling

## Overview

This project leverages machine learning to predict the risk of a borrower defaulting on a loan. It uses a fine-tuned **XGBoost** model, backed by feature engineering and resampling techniques, to assess credit risk with high accuracy. The project provides an interactive interface built with **Streamlit**, allowing users to input borrower details and get real-time predictions.

## Key Features

- **Model**: XGBoost with hyperparameter tuning and under-sampling
- **Metrics**: AUC: 0.98, Gini Coefficient: 0.97, KS Statistic: 86.87%
- **Interpretability**: SHAP and LIME for understanding model predictions
- **Deployment**: Pre-built pipeline for easy integration into business systems

## How It Works

1. **Input Borrower Data**: Enter details like age, income, loan amount, etc
2. **Get Real-time Results**: View default risk probability, credit score, and rating
3. **Analyze**: Understand risk insights with interactive visualizations like AUC-ROC and SHAP plots
