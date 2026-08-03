<img width="1427" height="827" alt="image" src="https://github.com/user-attachments/assets/ec32360c-bc09-4096-8316-b1429349fd9a" />

# 🎬 Movie Recommendation System

A full-stack Movie Recommendation System built using **FastAPI**, **Streamlit**, and **Machine Learning (NLP)**. The application recommends similar movies using **TF-IDF Vectorization** and **Cosine Similarity**, while fetching live movie information from the **TMDB API**.

---

## 🚀 Live Demo

Frontend:
(Add Streamlit URL)

Backend API:
(Add Render URL)

API Documentation:
https://your-render-url.onrender.com/docs

---

## 📌 Features

- 🔍 Movie Search with autocomplete
- 🎬 Content-based movie recommendations
- 🎭 Genre-based recommendations
- 🖼️ Live movie posters and backdrops
- ⭐ Ratings and popularity
- 📅 Release date and genres
- ⚡ FastAPI REST API
- 🌐 Streamlit interactive frontend

---

## 🛠 Tech Stack

### Frontend
- Streamlit
- Requests

### Backend
- FastAPI
- Uvicorn

### Machine Learning
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

### Data Processing
- Pandas
- NumPy
- NLTK

### APIs
- TMDB API

---

## 📂 Project Structure

```
movie-rec/
│
├── app.py                  # Streamlit Frontend
├── main.py                 # FastAPI Backend
├── requirements.txt
├── movies_metadata.csv
├── df.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
├── README.md
└── .gitignore
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/namits1ngh/movie-rec.git
cd movie-rec
```

Create virtual environment

```bash
python -m venv .venv
```

Activate

Windows

```bash
.venv\Scripts\activate
```

Linux / Mac

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
TMDB_API_KEY=YOUR_API_KEY
```

Run FastAPI

```bash
uvicorn main:app --reload
```

Run Streamlit

```bash
streamlit run app.py
```

---

## 🧠 Recommendation Engine

The recommendation engine combines:

- TF-IDF Vectorization
- Cosine Similarity
- NLP preprocessing
- Genre similarity
- TMDB metadata enrichment

---

## 📸 Screenshots

### Home Page

(Add Screenshot)

### Search

(Add Screenshot)

### Movie Details

(Add Screenshot)

### Recommendations

(Add Screenshot)

---

## 🌍 Deployment

Backend:
- Render

Frontend:
- Streamlit Community Cloud

---

## Future Improvements

- User authentication
- Watchlist
- Collaborative filtering
- Hybrid recommendation engine
- Trailer support
- Similar actors/directors
- Infinite scrolling
- Dark mode
- Docker deployment

---

## Author

**Namit Kumar Singh**

GitHub:
https://github.com/namits1ngh

LinkedIn:
(Add LinkedIn URL)

---

⭐ If you found this project useful, consider giving it a star!
