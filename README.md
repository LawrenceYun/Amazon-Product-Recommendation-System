# Amazon Product Recommendation System

## Overview
This MIT IDSS recommendation systems project builds and evaluates recommendation models using the Amazon Electronics product ratings dataset.

The original dataset contains 7,824,481 ratings across 4,201,696 users and 476,001 products. The project explores sparse user-product interaction data and develops recommendation models to predict user preferences.

## Dataset
- Source: Amazon Electronics ratings dataset used in MIT IDSS coursework
- File: `ratings_Electronics.csv`
- Original size: 7,824,481 ratings × 4 columns
- Unique users: 4,201,696
- Unique products: 476,001
- Columns: user ID, product ID, rating, timestamp

## Key Methods
- Large-scale ratings data preprocessing
- User-product interaction analysis
- Data filtering for model feasibility
- User-user collaborative filtering
- Item-item collaborative filtering
- Matrix factorization using SVD
- Hyperparameter tuning
- Recommendation generation
- Model evaluation using RMSE, precision, recall, and F1-score

## Key Results
The project compared multiple recommendation approaches, including:
- User-user similarity-based collaborative filtering
- Item-item similarity-based collaborative filtering
- Matrix factorization with SVD

The models were evaluated using rating prediction accuracy and recommendation quality metrics.

## Tech Stack
Python, pandas, NumPy, scikit-learn, scikit-surprise, Matplotlib, Seaborn, Jupyter Notebook / Google Colab

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/amazon_product_recommendation_system.ipynb

## Project Structure
```text
.
├── README.md
├── requirements.txt
├── notebooks/
│   └── amazon_product_recommendation_system.ipynb
├── data/
│   └── README.md
└── figures/
