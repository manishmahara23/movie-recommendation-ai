#  AI Movie Recommendation System

An intelligent **Movie Recommendation System** built using **Machine Learning, FastAPI, and Streamlit** that suggests similar movies and fetches real-time posters using the TMDB API.

This project demonstrates **end-to-end full-stack AI development** including ML model integration, REST API development, cloud deployment, and an interactive frontend.

---

#  Live Demo

###  Streamlit App (Frontend)

 https://movie-recommendation-ai-ml.streamlit.app/

### ⚡ FastAPI Backend (API Docs)

 https://movie-recommendation-ai-wdt8.onrender.com/docs

>  Note: Backend is hosted on free tier (Render). First request may take ~30 seconds to wake up.

---

#  Features

*  Search any movie instantly
*  Get top similar movie recommendations
*  Fetch real-time posters from TMDB API
*  FastAPI backend for fast responses
*  Interactive Streamlit UI
*  Content-based recommendation system using cosine similarity
*  Fully deployed (Frontend + Backend)

---

#  Tech Stack

## 🔹 Backend

* FastAPI
* Python
* REST APIs

## 🔹 Frontend

* Streamlit

## 🔹 Machine Learning

* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorization
* Cosine Similarity

## 🔹 Other Tools

* TMDB API
* Pickle
* Git & GitHub
* Render (Backend deployment)
* Streamlit Cloud (Frontend deployment)

---

#  System Architecture

User → Streamlit UI → FastAPI Backend → ML Model → TMDB API → Response → UI

This project follows a **production-level architecture** by separating ML logic into a backend API and connecting it to a frontend interface.

---

#  Project Structure

MovieRecommendation/
│
├── app.py               # Streamlit frontend
├── main.py              # FastAPI backend
├── df.pkl               # movie dataset
├── tfidf.pkl            # tfidf model
├── tfidf_matrix.pkl     # tfidf matrix
├── indices.pkl          # movie indices mapping
├── requirements.txt
├── runtime.txt          # python version for deployment
├── .python-version
├── .env                 # TMDB API key (not pushed)
└── README.md

---

#  Run Locally

##  Clone repository

git clone https://github.com/manishmahara23/movie-recommendation-ai.git
cd movie-recommendation-ai

##  Create virtual environment

python -m venv .venv
.venv\Scripts\activate

##  Install dependencies

pip install -r requirements.txt

##  Add TMDB API key

Create `.env` file and add:

TMDB_API_KEY=your_api_key_here

Get API key from:
https://www.themoviedb.org/settings/api

---

##  Run FastAPI backend

uvicorn main:app --reload

Open:
http://127.0.0.1:8000/docs

##  Run Streamlit frontend

Open new terminal:

streamlit run app.py

Open:
http://localhost:8501

---

#  Future Improvements

* User authentication system
* Collaborative filtering
* Watchlist feature
* Hybrid recommendation system
* Deep learning recommendations
* Docker deployment

---

#  Author

**Manish Mahara**
Aspiring Software Developer | AI/ML Enthusiast

GitHub:
https://github.com/manishmahara23

---

# ⭐ If you like this project

Give it a star on GitHub — it helps!
