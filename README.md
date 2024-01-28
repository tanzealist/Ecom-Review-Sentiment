# Sentiment Analysis with Naive Bayes Classifier (NBC)

## Introduction
This project, "E-Commerce Emotions," leverages Naive Bayes Classification to analyze sentiments in e-commerce product reviews. By scraping around 10,000 reviews, each review is labeled as negative or positive based on its rating, with the application of tokenization and stemming for textual data preparation.

## Dataset
The dataset comprises approximately 10,000 product reviews. Each review has been labeled as:
- **Negative**: If the rating is 1 or 2.
- **Positive**: If the rating is 4 or 5.

## Methodology
- Web scraping was performed to collect the dataset.
- Data preprocessing included tokenization and stemming.
- A Naive Bayes Classifier was trained on the dataset.
- The model was evaluated with an 80/20 train/test split.

## Dependencies
- pandas
- numpy
- scikit-learn
- nltk
- beautifulsoup4

## Exploratory Data Analysis (EDA)
We performed EDA to understand the distribution and common traits within the dataset.

<p align="center">
  <img src="path_to_eda_image.png" alt="EDA Visualization">
</p>

## Model Training and Evaluation
The NBC model was trained and its performance was evaluated using accuracy, precision, recall, and F1-score metrics.

<p align="center">
  <img src="path_to_model_evaluation_image.png" alt="Model Evaluation">
</p>

## Conclusion

Our sentiment analysis project effectively applied machine learning to classify Amazon product reviews from Trustpilot.com. We employed natural language processing to preprocess data, and our Naive Bayes Classifier, optimized via GridSearchCV, achieved an accuracy of 89%, precision of 87%, recall of 89%, and an F1-score of 87%. The model's performance, visualized through various plots, demonstrates its reliability in discerning customer sentiments, providing actionable insights for enhancing user experience and business offerings.

