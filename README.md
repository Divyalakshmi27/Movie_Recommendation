# Movie_Recommendation
# 🎬 Movie Recommendation System

A hybrid movie recommendation system built using content-based and collaborative filtering techniques on TMDB's 5000+ movie dataset.

## 📁 Datasets Used
- [`tmdb_5000_movies.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [`tmdb_5000_credits.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## 🔍 Features
- **Content-Based Filtering:** Uses genres, overview, cast, and crew.
- **Collaborative Filtering:** Uses user-based similarity with cosine similarity.
- **Hybrid Model:** Combines both models with weighted scoring.
- **Visualization:** Popular genres visualized using Seaborn.

## 🧠 Techniques Used
- Natural Language Processing with TF-IDF
- Cosine Similarity
- MinMax Scaling
- Feature Engineering
- Data Merging and Cleaning

## 🛠 Libraries & Tools
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

## 📊 Output Examples
- Content-based recommendations for a given movie
- User-based collaborative filtering recommendations
- Hybrid movie recommendations
- Genre frequency bar plot

## ▶️ Example Usage
```python
get_content_based_recommendations('Avatar')
get_collaborative_recommendations('user1')
get_hybrid_recommendations('user1', 'Avatar')

