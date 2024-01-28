# Sentiment Analysis with Naive Bayes Classifier (NBC) and Web Scrapping

## Introduction
This project, "E-Commerce Emotions," leverages Naive Bayes Classification to analyze sentiments in e-commerce product reviews. By scraping around 10,000 reviews, each review is labeled as negative, neutral or positive based on its rating, with the application of tokenization and stemming for textual data preparation.

## Dataset
The dataset comprises approximately 10,000 product reviews. Each review has been labeled as:
- **Negative**: If the rating is 1 or 2.
- **Neutral**: If the rating is 3.
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

## Run this Project
To run this project you need to run below pynb files:

jupyter notebook web_scrapping.ipynb

jupyter notebook nbc_tanuj.ipynb

Refer to PPT and python files for flow of the project

## Web Scrapping and Data Collection

Python's Beautiful Soup library was employed to automate the scraping of customer reviews from Trustpilot's Amazon page. We iterated over multiple pages to capture review texts and ratings, storing the information in a Pandas dataframe for subsequent analysis.

<p align="center">
  <img width="800" alt="image" src="https://github.com/tanzealist/-Sentiment-Analysis-with-Naive-Bayes-Classifier-NBC-and-Web-Scrapping/assets/114698958/5b5ee9c7-8018-4891-b1d7-b81a22936bd4">



## Exploratory Data Analysis (EDA)
We performed EDA to understand the distribution and common traits within the dataset.

<p align="center">
  <img width="800" alt="Screenshot 2024-01-28 at 9 32 52 AM" src="https://github.com/tanzealist/-Sentiment-Analysis-with-Naive-Bayes-Classifier-NBC-and-Web-Scrapping/assets/114698958/323c60a3-3e63-4075-acdc-24d91b8ac79e">


## Model Training and Evaluation
The NBC model was trained and its performance was evaluated using accuracy, precision, recall, and F1-score metrics.

<p align="center">
  <img width="800" alt="Screenshot 2024-01-28 at 9 34 19 AM" src="https://github.com/tanzealist/-Sentiment-Analysis-with-Naive-Bayes-Classifier-NBC-and-Web-Scrapping/assets/114698958/e75fefc6-1c8f-4a7d-9f0a-a5416a87e5cb">


## Conclusion

Our sentiment analysis project effectively applied machine learning to classify Amazon product reviews from Trustpilot.com. We employed natural language processing to preprocess data, and our Naive Bayes Classifier, optimized via GridSearchCV, achieved an accuracy of 89%, precision of 87%, recall of 89%, and an F1-score of 87%. The model's performance, visualized through various plots, demonstrates its reliability in discerning customer sentiments, providing actionable insights for enhancing user experience and business offerings.

