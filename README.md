# Instacart Market Basket Analysis

This project aims to build a product recommendation system using Instacart’s dataset. It uses machine learning models like LightGBM with Optuna for hyperparameter tuning, and post-processing for improving prediction thresholds.

## Project Structure

├── data/ # Raw and processed data (ignored by Git)
├── db/ # Any database-related files (ignored by Git)
├── model.pkl # Saved ML model (ignored by Git)
├── notebooks/ # Jupyter Notebooks for EDA and development
├── src/ # Source code for features, training, utils, etc.
├── .gitignore # Git ignore rules
├── requirements.txt # Python dependencies
├── README.md # This file

markdown
Copy code

## Features Implemented

- Feature engineering (user-product interaction, recency, reorder ratio, etc.)
- LightGBM model with Optuna tuning
- Precision-Recall Curve and threshold optimization
- Final model saved as `.pkl`

## Results

- **F1 Score (Class 1)**: ~0.42 (with threshold tuning)
- **Macro Avg F1**: ~0.69

## Next Steps

- Predict products per user in the test set
- Build a chatbot interface for product recommendations
- (Optional) Build a small front-end app for visualization & predictions
