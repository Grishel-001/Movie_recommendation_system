🎬 Movie Recommendation System

This project is a Content-Based Movie Recommendation System that suggests movies similar to a selected film. It uses machine learning techniques to compute similarity between movies and displays the top 5 recommendations along with their posters using data from the TMDb API. The application is deployed using Streamlit for an interactive user interface.

⭐ Features

Suggests Top 5 similar movies

Uses content-based filtering with cosine similarity

Fetches movie posters via TMDb API

Simple and interactive Streamlit UI

Handles missing posters and connection errors gracefully

🧠 How It Works

Movie metadata is preprocessed and vectorized

Similarity scores are calculated using cosine similarity

When a user selects a movie, the system retrieves and displays the most similar movies

Posters are fetched through the TMDb API

🛠️ Technologies Used

Python

Pandas

Streamlit

Requests

Pickle

TMDb API

📁 Files Included

app.py – Streamlit application

movies_dict.pkl – Movie data (titles, IDs)

similarity.pkl – Precomputed similarity matrix  
