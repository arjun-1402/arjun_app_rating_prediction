# App Rating Prediction using NLP

## Problem Overview
Predict Google Play Store app ratings (1–5) using user reviews and metadata.

## Approach
- Combined review title and review text
- Applied TF-IDF with unigrams and bigrams
- Trained a Logistic Regression classifier

## Feature Extraction
- TF-IDF (1,2 n-grams)
- Stopword removal
- Lowercasing

## Validation
- Stratified 80/20 train-validation split
- Evaluation metric: Weighted F1-score

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run the Jupyter Notebook in `src/`
3. Generated predictions saved as `predictions.csv`

