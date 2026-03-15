## Movie Recommendation System

A **content-based movie recommendation system** built with **Python, Natural Language Processing (NLP), and Machine Learning** that suggests movies similar to the one selected by the user.

The system analyzes movie metadata such as **genres, keywords, and overview text**, then calculates similarity between movies to recommend relevant titles.

---

##  Features

* Recommend movies based on **content similarity**
* Uses **Natural Language Processing (NLP)** techniques
* Calculates similarity using **TF-IDF Vectorization** and **Cosine Similarity**
* Simple and easy to extend for **web apps or streaming platforms**

---

##  How It Works

1. Load the movie dataset
2. Clean and preprocess the data
3. Combine important textual features:

   * genres
   * keywords
   * overview
4. Convert text into numerical vectors using **TF-IDF**
5. Compute similarity scores using **cosine similarity**
6. Return the most similar movies to the selected one

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Cosine Similarity
* Jupyter Notebook

---

## Example Recommendation

Input movie:

```
The Dark Knight
```

Recommended movies:

```
Batman Begins
The Dark Knight Rises
Man of Steel
Watchmen
V for Vendetta
```

##  Project Structure

```
movie-recommendation-system
│
├── Movie_Recommendation.ipynb
├── movies_dataset.csv
├── README.md
└── images
    └── banner.png
```

##  Future Improvements

---
* Build a **web interface with Flask or Streamlit**
* Add **user-based collaborative filtering**
* Deploy the system as a **web application**

---

## 👨‍💻 Author

Developed by **Sama Alsharkabaly**

Machine Learning & AI Enthusiast
