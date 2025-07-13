# 🎬 Movie Recommendation System

A content-based movie recommender app that suggests similar movies using metadata like genres, cast, crew, and overviews. Built using Python and Streamlit, it provides a clean UI and real-time poster previews via the TMDB API.

## 📸 Demo

![App Screenshot](screenshots/demo.gif)

## 🚀 Features

- Search for any movie
- Get top 5 similar movies with posters
- Fast, interactive UI using Streamlit

## 🧠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- TMDB API

## 🛠️ Installation

git clone https://github.com/Arkarup-2025/movie-recommendation-system.git
cd movie-recommendation-system
pip install -r requirements.txt
streamlit run app.py

## Manual Tree Structure

📦 project-name
├── app.py
├── data/
│   └── movies.csv
├── model/
│   └── similarity.pkl
├── screenshots/
│   └── demo.gif
├── requirements.txt
└── README.md
