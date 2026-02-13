# 🎬 AI Movie Recommendation System

An intelligent **Movie Recommendation System** built using **Machine Learning, FastAPI, and Streamlit** that suggests similar movies and fetches real-time posters using the TMDB API.

This project demonstrates end-to-end AI development including ML model integration, API development, and an interactive frontend.

---

## 🚀 Features

* 🔍 Search any movie
* 🎯 Get top similar movie recommendations
* 🖼 Fetch movie posters from TMDB API
* ⚡ FastAPI backend for high-speed responses
* 💻 Interactive Streamlit UI
* 🤖 Content-based recommendation system using cosine similarity

---

## 🧠 Tech Stack

**Backend**

* FastAPI
* Python
* REST APIs

**Frontend**

* Streamlit

**Machine Learning**

* Pandas
* NumPy
* Scikit-learn
* Cosine Similarity

**Other Tools**

* TMDB API
* Pickle
* Git & GitHub

---

## 📂 Project Structure

```
MovieRecommendation/
│
├── app.py               # Streamlit frontend
├── main.py              # FastAPI backend
├── df.pkl               # movie dataset
├── tfidf.pkl            # tfidf model
├── tfidf_matrix.pkl     # tfidf matrix
├── indices.pkl          # movie indices mapping
├── requirements.txt
├── .env                 # TMDB API key (not pushed)
└── README.md
```

---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone repository

```
git clone https://github.com/manishmahara23/movie-recommendation-ai.git
cd movie-recommendation-ai
```

### 2️⃣ Create virtual environment

```
python -m venv .venv
.venv\Scripts\activate
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Add TMDB API key

Create `.env` file in root folder and add:

```
TMDB_API_KEY=your_api_key_here
```

Get API key from: https://www.themoviedb.org/settings/api

### 5️⃣ Run FastAPI backend

```
uvicorn main:app --reload
```

Open:

```
http://127.0.0.1:8000/docs
```

### 6️⃣ Run Streamlit frontend

Open new terminal:

```
streamlit run app.py
```

Open:

```
http://localhost:8501
```

---

## 📸 Demo Preview

(Add screenshots here after running project)

Suggested screenshots:

* Homepage UI
* Movie recommendation results
* FastAPI docs

---

## 💡 Future Improvements

* User login & authentication
* Collaborative filtering
* Deploy on cloud (Render/Streamlit cloud)
* Add watchlist feature
* Improve recommendation accuracy using deep learning

---

## 🧑‍💻 Author

**Manish Mahara**
Aspiring Software Developer | AI/ML Enthusiast

GitHub: https://github.com/manishmahara23
