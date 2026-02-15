
# 🎬 IMDB Movie Recommendation System

A Movie Recommendation System built using Python that suggests similar movies based on user input. This project demonstrates how machine learning techniques can be used to analyze movie data and generate personalized recommendations.

---

## 📌 Project Overview

This system recommends movies similar to a given movie by analyzing features such as genres and user ratings. It uses both:

* **Content-based filtering** – recommends movies based on similarity between movie features (genres)
* **Collaborative filtering** – recommends movies based on similarity between users using Pearson correlation

The project is implemented in a **Jupyter Notebook** and focuses on understanding recommendation system logic and similarity calculations.

---

## 🚀 Features

* Accepts a movie name as input from the user
* Recommends top 10 similar movies
* Uses similarity metrics to find related movies
* Implements both content-based and collaborative filtering techniques
* Demonstrates real-world machine learning application

---

## 🧠 How It Works

### 1. Data Preprocessing

* Loaded movie and ratings datasets using Pandas
* Cleaned and formatted movie titles and genres
* Converted genres into numerical format using vectorization

### 2. Content-Based Filtering

* Used **CountVectorizer** to convert genres into numeric vectors
* Used **Cosine Similarity** to calculate similarity between movies
* Recommended movies with highest similarity scores

### 3. Collaborative Filtering

* Used **Pearson Correlation** to find similar users
* Recommended movies liked by users with similar preferences

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## 📂 Dataset

* movies.csv – contains movie titles and genres
* ratings.csv – contains user ratings for movies

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

2. Open the Jupyter Notebook

```bash
jupyter notebook
```

3. Run all cells

4. Enter a movie name when prompted

Example:

```
Enter movie name: Batman
```

Output:

```
Recommended movies:
Batman Forever
The Dark Knight
Batman Begins
...
```

---

## 📈 Learning Outcomes

Through this project, I learned:

* How recommendation systems work
* Difference between content-based and collaborative filtering
* How to preprocess and analyze real-world datasets
* How to calculate similarity using cosine similarity and Pearson correlation
* How to implement machine learning logic using Python

---

## 🔮 Future Improvements

* Add web interface using Flask or Streamlit
* Improve recommendations using more features
* Deploy as a web application
* Use advanced ML models


