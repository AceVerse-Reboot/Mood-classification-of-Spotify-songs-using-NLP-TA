# Mood Classification of Spotify Songs Using NLP and Text Analysis

This 2025–26 final-year project explores how Spotify song titles can be used to classify tracks into four mood categories: **happy, sad, love, and party**. It also builds a recommendation system that combines title similarity, mood, and track popularity.

**[View the Jupyter notebook on GitHub](./FYP_KUMRUALAGUR.ipynb)**

## What the notebook covers

- Preprocessing song titles through tokenisation, stop-word removal, and stemming.
- Exploring sentiment and vocabulary patterns across the four mood categories.
- Comparing four classifiers: logistic regression, multinomial naïve Bayes, linear support vector machine, and random forest.
- Generating recommendations for titles in the dataset and for new title queries using TF-IDF and cosine similarity.

## Running the notebook

To run the notebook, place `spotify_songs_eda.csv` in the same folder as `FYP_KUMRUALAGUR.ipynb`. The dataset is required and is not included in this fork.

## Credits

Original project by **Kumru Alagur**. [View the original repository](https://github.com/kumrualagur/FYP-KUMRU-ALAGUR-).

## Evaluation extension

[View the unseen-title evaluation notebook](./mood_evaluation.ipynb)

This extension compares four classifiers on the dataset’s original and keyword-revised mood labels. Both evaluations use the same held-out songs, with repeated titles kept together to avoid overlap between training and testing.

Results are pending access to the original `spotify_songs_eda.csv` dataset.
