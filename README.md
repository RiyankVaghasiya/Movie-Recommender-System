# 🎬 Movie Recommender System

A content-based movie recommendation system built using **Python**, **Pandas**, **scikit-learn**, and **Streamlit**. It recommends movies based on similarity in content such as cast, crew, genre, and more.

![image](https://github.com/user-attachments/assets/080cc6e0-2015-4232-b85c-f322bde165ee)


## 🚀 Features

- 🔍 Search for your favorite movie
- 📽️ Get top similar movie recommendations
- 📚 Content-based filtering using metadata (tags, cast, genres, etc.)
- 🧠 Uses **CountVectorizer** and **cosine similarity** for recommendation
- ⚡ Built with a fast and interactive **Streamlit** web interface

---

---

## 🧠 How It Works

1. Data is cleaned and merged from `movies.csv` and `credits.csv`
2. Text data like genres, cast, director, and keywords are combined into a "tags" column
3. `CountVectorizer` transforms the tags into a matrix of token counts
4. Cosine similarity is calculated to find similar movies
5. Streamlit displays results interactively in a browser

---
