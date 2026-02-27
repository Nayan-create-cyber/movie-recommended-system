# 🎬 Movie Recommender System

A **content-based Movie Recommendation System** built using **Python and Streamlit**.  
The app recommends movies similar to the one selected by the user and displays their posters using the **TMDB API**.

---

##  Live Demo
 https://movie-recommended-system-tprdpkhpxm9jceqw8taead.streamlit.app/

---

##  Tech Stack
- Python
- Streamlit
- Pandas
- NumPy
- TMDB API
- Git & GitHub
- Git LFS (for large ML files)

---

##  Features
- Select a movie and get **5 similar movie recommendations**
- Displays **movie posters** fetched from TMDB
- Fast recommendations using a **precomputed similarity matrix**
- Secure API key handling using **Streamlit Secrets**
- Deployed on **Streamlit Community Cloud**

---

##  How It Works
1. Movie data is processed and vectorized
2. **Cosine similarity** is calculated between movies
3. When a user selects a movie, the most similar movies are recommended
4. Posters are fetched dynamically using the TMDB API



