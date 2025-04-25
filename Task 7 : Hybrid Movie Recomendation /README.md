# 🎬 Hybrid Movie Recommendation System

This project is a **Hybrid Movie Recommender System** that combines **Collaborative Filtering** and **Content-Based Filtering** techniques. It uses **TMDb API** to fetch movie posters and metadata, and is deployed with **Streamlit** on a temporary URL using **LocalTunnel**.

## 🚀 Features

- Hybrid recommendation using:
  - User ratings (Collaborative Filtering)
  - Genre similarity (Content-Based Filtering)
- Integrated with **TMDb API** for movie posters
- Clean and interactive UI using Streamlit
- Easily accessible in browser via LocalTunnel
- Built with Python and pandas, scikit-learn

---

## 🧠 How It Works

- Collaborative Filtering: Based on user-item interactions
- Content-Based Filtering: Based on movie genres
- Poster Images: Fetched using the TMDb API via HTTP requests
- Recommendations are ranked and returned with poster previews

---

## 📁 Dataset Used

- `movies.dat`: Movie ID, Title, Genre
- `ratings.dat`: User ID, Movie ID, Rating, Timestamp
