# Twitter-X-Sentiment-Analysis

Sentiment analysis using TF-IDF and classification models to evaluate public sentiment on Twitter (X), supported by interactive Power BI visualizations.

A case study in text mining and machine learning that explores sentiment trends from tweets across demographics and posting times, using both predictive modeling and dashboard analytics.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preprocessing & EDA](#data-preprocessing--eda)
- [Modeling](#modeling)
- [Dashboard](#dashboard)
- [Results](#results)
- [Supplementary Documents](#supplementary-documents)
- [Summary](#summary)
- [How to Run](#how-to-run)
- [Contact](#contact)

---

## Overview

This project analyzes tweet sentiment using machine learning techniques (Logistic Regression, Naive Bayes, SVM). Tweets were vectorized using TF-IDF, and Power BI was used for data visualization. The project investigates sentiment trends across age groups and time of day and provides insights useful for marketing and social monitoring.

---

## Dataset

- **Source:** [Kaggle - Sentiment Analysis Dataset](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset)
- **Size:** ~45,000 tweets
- **Features:**
  - `TextID`
  - `Text`
  - `Sentiment` (positive, neutral, negative)
  - `Time of Tweet` (morning, noon, night)
  - `Age of User`
  - `Country`

📁 [Download Dataset (CSV)](Dataset.csv)

---

## Data Preprocessing & EDA

- Cleaned tweets: lowercasing, removed URLs, mentions, hashtags, punctuation
- Explored sentiment distribution, word counts, tweet lengths, hashtag/mention frequency
- Visualized sentiment vs. age group and tweet timing
- Generated word clouds by sentiment

📓 [View Jupyter Notebook](Twitter_Sentiment_Analysis.ipynb)

---

## Modeling

- **Vectorization:** TF-IDF with 5000 features
- **Train/Test Split:** 80/20 stratified
- **Models Evaluated:**
  - Logistic Regression – *Best Accuracy: 64%, Specificity: 81%*
  - Naive Bayes – *Accuracy: 59%*
  - SVM – *Accuracy: 62%*

---

## Dashboard

Power BI dashboard visualizes:
- Sentiment by time of day (morning, noon, night)
- Sentiment distribution by age group
- Sentiment class proportions

📊 [View Dashboard](https://github.com/KiruthikaRamadoss/Twitter-X-Sentiment-Analysis/blob/main/Power%20BI%20Dashboard.pdf)

---

## Results

- **Best Model:** Logistic Regression
- **Sentiment Distribution:**
  - Neutral: 53.9%
  - Positive: 26.0%
  - Negative: 20.1%
- **Business Use Cases:**
  - Real-time social media monitoring
  - Brand sentiment analysis
  - Public opinion tracking

---

## Supplementary Documents

📊 [Presentation Slides](https://drive.google.com/file/d/1n3BgcOZsbbXaC-4CZ0RhLEnZzobyTVSi/view?usp=drive_link)  

📄 [Term Paper](https://drive.google.com/file/d/1RSIwaDRjuj2LDRR6rGxS57Lkq8QUDsrC/view?usp=drive_link)

*Note: Documents are shared as view-only to preserve originality and prevent unauthorized edits.*


---

## Summary

- Demonstrated the use of TF-IDF and ML models to classify tweet sentiments.
- Logistic Regression showed the best performance among tested models.
- EDA revealed sentiment patterns by age and time of tweet, useful for marketing analytics.
- Power BI provided effective data storytelling through interactive visualizations.
- Reinforced the value of NLP and business intelligence in social media analysis.

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/KiruthikaRamadoss/Twitter-X-Sentiment-Analysis.git
   cd Twitter-X-Sentiment-Analysis


2. Create and activate a virtual environment (Optional):
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

4. Install dependencies:
   pip install -r requirements.txt

6. Launch the notebook:
jupyter notebook Twitter_Sentiment_Analysis.ipynb


   ## Contact

For inquiries, feedback, or professional connections:

- [LinkedIn](https://www.linkedin.com/in/kiruthikaramadoss/)
- [GitHub](https://github.com/KiruthikaRamadoss)  
- [Email](mailto:k_r549@txstate.edu)
