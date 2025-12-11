# Hull Tactical Market Prediction - Final Project

**Student:** Divit Pratap Singh  
**Course:** Machine Learning  
**Competition:** [Kaggle Hull Tactical](https://www.kaggle.com/competitions/hull-tactical-market-prediction)

## Project Overview
Predicting S&P 500 daily excess returns using machine learning techniques.

## Results
- **Information Coefficient (IC):** 0.068
- **Kaggle Score:** 3.489
- **Models:** Ridge, XGBoost, LightGBM Ensemble

## Repository Structure
- `Final_Project.ipynb` - Complete analysis with all code
- `results/` - Model outputs and performance metrics
- `data/` - Training data (download from Kaggle)

## Team
- Divit Pratap Singh (Solo Project - 100% contribution)

## Data
Download the competition data from Kaggle:
https://www.kaggle.com/competitions/hull-tactical-market-prediction/data

Place the files in the `data/` directory:
- `train.csv` - Training dataset (9,021 samples, 94 features)
- `test.csv` - Test dataset

## Requirements
```
numpy==1.24.3
pandas==2.0.3
scikit-learn==1.3.0
xgboost==2.0.0
lightgbm==4.0.0
scipy==1.11.2
matplotlib==3.7.2
seaborn==0.12.2
```

Install all: `pip install -r requirements.txt`
