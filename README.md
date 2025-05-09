# content_based_recommender

This project implements a content-based filtering recommendation system using the **MIND (Microsoft News Dataset)**. The system recommends news articles to users based on content similarity using **TF-IDF** and **cosine similarity**.
## 📌 Features

- Preprocesses the MIND dataset (`news.tsv`)
- Cleans and combines title + abstract content
- Extracts TF-IDF features from articles
- Constructs a simple user profile based on preferred keywords
- Computes cosine similarity between articles and the user profile
- Recommends the top-N most relevant news articles

- ## 🗃 Dataset

**Microsoft News Dataset (MIND):**  
Download from [Kaggle](https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data)

## 📁 Project Structure

content_based_news_recommender/
│
├── data/
│ └── news.tsv
│
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_user_profile_construction.ipynb
│ ├── 03_content_similarity.ipynb
│ └── 04_ranking_and_recommendation.ipynb
│
├── results/
│ ├── sample_recommendations.csv
│ └── user_feedback_notes.txt
│
├── requirements.txt
└── README.md
