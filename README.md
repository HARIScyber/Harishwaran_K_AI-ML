# Harishwaran_K_AI-ML
# Fake News Detection using Machine Learning 

This project builds a machine learning model to classify news articles as **Fake** or **Real** using Natural Language Processing (NLP) techniques.

## Project Overview

Fake news detection is an important NLP classification problem.
This project preprocesses text data, converts it into numerical features using TF-IDF, and trains a classification model.

## Dataset

Fake News Dataset

Contains:

* Title
* News Text
* Label (Fake / Real)

## Workflow

* Data Loading
* Data Cleaning
* Text Preprocessing
* Data Visualization
* Train/Validation/Test Split (70:10:20)
* Feature Extraction using TF-IDF
* Model Training using Logistic Regression
* Model Evaluation

## Data Visualizations

* Fake vs Real News Distribution
* News Article Length Distribution
* Most Common Words
* Word Cloud Visualization
* Confusion Matrix

## Model Used

* TF-IDF Vectorizer
* Logistic Regression

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* AUC-ROC

## Installation

```bash
pip install -r requirements.txt
```
## Run

Open:
Fake_News_Detection.ipynb

Run all cells in Google Colab or Jupyter Notebook.

## Reproducibility

* Fixed random seed = 42
* Train/Validation/Test split = 70:10:20
* Complete preprocessing steps included
* Dependencies listed

## Limitations

* Performance depends on dataset quality
* Hard to detect highly manipulated fake news
* Context understanding is limited

# Movie Recommendation System 

This project builds a machine learning-based recommendation system to predict movie ratings using the MovieLens-100K dataset.

## Project Overview

The goal of this project is to predict the rating a user would give to a movie they have not rated yet.

## Dataset

MovieLens-100K Dataset

Contains:

* User IDs
* Movie IDs
* Ratings
* Timestamps

## Workflow

* Data Loading
* Data Cleaning
* Data Visualization
* Train/Validation/Test Split (70:10:20)
* Model Training using KNN Regressor
* Rating Prediction
* Model Evaluation

## Data Visualizations

* Ratings Distribution
* Top Active Users
* Most Rated Movies
* Average User Ratings
* Actual vs Predicted Ratings

## Model Used

* K-Nearest Neighbors Regressor (KNN)

## Evaluation Metrics

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)

## Installation

```bash
pip install -r requirements.txt
```

## Run

Open:
Movie_Recommendation_System.ipynb

Run all cells in Google Colab or Jupyter Notebook.

## Reproducibility

* Fixed random seed = 42
* Train/Validation/Test split = 70:10:20
* Full preprocessing documented
* Dependencies listed

## Limitations

* Cold start problem
* Sparse user-item matrix
* Scalability issues with large datasets




