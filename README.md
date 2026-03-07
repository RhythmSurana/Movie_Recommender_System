# 🎬 Movie Recommender System

A **Content-Based Movie Recommendation System** built using **Python, Machine Learning, and Streamlit**.  
This application recommends movies similar to the one selected by the user and displays their posters using the TMDB API.

---

## 🚀 Features

- Recommend **5 similar movies**
- Displays **movie posters**
- Interactive **Streamlit web interface**
- Fast recommendations using **vectorizer** and **cosine similarity**
- Uses **TMDB API** to fetch movie posters

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Streamlit
- Pickle
- Requests API
- TMDB API

---

## 📂 Project Structure

```
Movie-Recommender-System
│
├── movie_recommend.py        # Streamlit app
├── movie_list.pkl            # Movie dataset
├── similarity.pkl            # Similarity matrix
├── movie_recommender.ipynb   # Model creation
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```
git clone https://github.com/your-username/movie-recommender-system.git
```

Go to the project directory

```
cd movie-recommender-system
```

Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Run the Streamlit app:

```
streamlit run movie_recommend.py
```

The app will open in your browser at:

```
http://localhost:8501
```

---

## 🔑 API Setup

This project uses **TMDB API** to fetch movie posters.

Steps:

1. Create an account on https://www.themoviedb.org/
2. Generate an API key
3. Replace the API key in the code

```python
api_key = "YOUR_API_KEY"
```

---

## 🧠 How It Works

1. Movie dataset is processed using **content-based filtering**
2. A **similarity matrix** is created using **cosine similarity**
3. When a user selects a movie:
   - Similar movies are retrieved
   - Posters are fetched from TMDB API
4. Results are displayed using **Streamlit UI**

---

## 📸 Screenshot

Add your application screenshot here

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/58d78d82-1900-4297-bf02-1e4408aeff3c" />

---

## 🌟 Future Improvements

- Add movie **ratings and overview**
- Add **search functionality**
- Improve UI design
- Deploy on **Streamlit Cloud**

---

## 👨‍💻 Author

Rhythm

GitHub: https://github.com/rhythmsurana
