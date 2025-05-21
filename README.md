
# 🎬 Movie Recommendation System using Machine Learning

## 📌 Project Description
This project is a **content-based movie recommendation system** developed using machine learning and natural language processing techniques. The system suggests movies similar to a user’s choice based on metadata such as genres, cast, crew, and keywords. It demonstrates key concepts in feature engineering, similarity measurements, and data preprocessing.

---

## 🧠 Key Features

- Load and clean movie metadata from a CSV file.
- Combine important text-based features (genres, cast, crew, keywords).
- Apply text vectorization using CountVectorizer.
- Calculate similarity scores using Cosine Similarity.
- Recommend top 5 most similar movies for a given movie title.

---

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - `pandas`
  - `scikit-learn`
  - `numpy`
  - `nltk`
- **Techniques**:
  - Count Vectorization
  - Cosine Similarity
  - NLP Feature Engineering
- **Platform**: Jupyter Notebook

---

## 📂 Project Structure

```
Movie_Recommendation_using_ML.ipynb
DataSet/
    └── movies.csv
README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Place the `movies.csv` file in a folder named `DataSet`.
3. Run the Jupyter Notebook `Movie_Recommendation_using_ML.ipynb`.
4. Execute the final cell to input a movie name and get recommendations.

---

## ✅ Future Enhancements

- Add a web interface using **Streamlit** or **Flask**.
- Integrate with **TMDB API** for richer movie information.
- Handle the cold-start problem using **collaborative filtering**.
- Improve ranking with popularity and IMDb rating filters.

---

## 🙌 Acknowledgements

- The dataset used in this project was originally sourced from [Kaggle](https://www.kaggle.com/).
- Techniques inspired by common ML recommendation system tutorials.

---

## 📧 Contact

Feel free to reach out to me for feedback or collaboration!

