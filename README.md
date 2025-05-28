# Twitter-X-Sentiment-Analysis
Sentiment analysis using TF-IDF and classification models to evaluate public sentiment on Twitter (X), supported by interactive Power BI visualizations.

A case study in text mining and machine learning that explores sentiment trends from tweets across demographics and posting times, using both predictive modeling and dashboard analytics.

## Table of Contents

- [Overview](#overview)
- [Team Members](#team-members)
- [Dataset](#dataset)
- [Data Preprocessing & EDA](#data-preprocessing--eda)
- [Modeling](#modeling)
- [Dashboard](#dashboard)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Contact](#contact)

---

## Overview

This project analyzes tweet sentiment using machine learning techniques (Logistic Regression, Naive Bayes, SVM). Tweets were vectorized using TF-IDF, and Power BI was used for data visualization. The project investigates sentiment trends across age groups and time of day and provides insights useful for marketing and social monitoring.

---

## Team Members
- Gowthami Sindhu Priya Chilukuri  
- Hinduja Cheela  
- Kiruthika Ramadoss  
- Musaddiqa Azeez  
- Sinan Salim  

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

🖼️ ![Dashboard](Dashboard%20Twitter%20project.png)

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

## Conclusion

- Logistic Regression outperformed more complex models.
- TF-IDF is effective for tweet classification.
- Data preprocessing is critical for social media analytics.
- Power BI enhances interpretation for non-technical users.

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YourUsername/Twitter-Sentiment-Analysis.git
   cd Twitter-Sentiment-Analysis

2. (Optional) Create and activate a virtual environment:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

4. Install dependencies:
   pip install -r requirements.txt

6. Launch the notebook:
jupyter notebook Twitter_Sentiment_Analysis.ipynb


   ## Contact

   For any inquiries or collaboration opportunities:

- [LinkedIn](https://www.linkedin.com/in/kiruthikaramadoss/)
- [GitHub](https://github.com/KiruthikaRamadoss)  
- [Email](mailto:k_r549@txstate.edu)
