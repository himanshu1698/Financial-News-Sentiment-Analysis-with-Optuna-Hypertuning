# Financial News Sentiment Analysis with Optuna Hypertuning

---

## Overview

This project performs sentiment analysis on a financial news dataset. The goal is to predict sentiment labels (e.g., positive, negative, neutral) based on the content of news articles. Sentiment analysis can provide valuable insights for traders, investors, and financial analysts.

## Dataset

The dataset used for this project contains two main columns:

- `sentiment`: This column contains the sentiment labels (e.g., positive, negative, neutral).
- `text`: This column contains the text of financial news articles.

You can find the dataset used in this project all_data.csv

## Project Structure

The project is organized into the following main sections:


1. **Data Cleaning and Preprocessing**: Text data is cleaned, including punctuation removal, lowercasing, stop-word removal, and stemming or lemmatization. Sentiment scores are calculated, and labels are assigned.


2. **Model Building**: The dataset is split into training and testing sets. Several NLP models are trained, including Random Forest and XGBoost. Hyperparameter tuning is performed to optimize model performance. Optuna is used currently for hypertuning the Xgboost model.

3. **Model Evaluation**: Model performance is evaluated using metrics like accuracy, precision, recall, and F1-score.

4. **Deployment (Optional)**: If desired, the model can be deployed for real-time predictions via a web application or API.

