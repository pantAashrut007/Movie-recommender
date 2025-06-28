# 🎬 AI-Powered Movie Recommendation System

This is a Python-based Movie Recommendation System that uses collaborative filtering to suggest movies similar to a user’s favorite. It leverages user ratings from the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/) and includes **fuzzy string matching** so users can input partial movie names or with typos. This project demonstrates core concepts of unsupervised learning and recommendation engines.

---

## 🚀 Features

- Collaborative filtering using Pearson correlation
- Fuzzy matching for flexible movie title input (e.g., "star war" → "Star Wars (1977)")
- Filter out noisy data (low-rating-count movies/users)
- Interactive user input via terminal
- Clean top 10 recommendations printed with rating counts

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- FuzzyWuzzy (`fuzzywuzzy[speedup]`)
- Google Colab or Jupyter Notebook

---

## 📂 Dataset

MovieLens 100k Dataset:
- Download: [GroupLens Official Site](https://grouplens.org/datasets/movielens/100k/)
- Files used:
  - `u.data`: User ratings (100k ratings)
  - `u.item`: Movie metadata (title, genre, release year)

Place both files in your project root directory.

---

## 🛠️ How to Run This Project

### Option 1: Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `u.data` and `u.item` files using the file sidebar
3. Copy and paste the code from `movie_recommender.ipynb`
4. Run all cells
5. When prompted, enter a movie name like:

```bash
Enter a movie name: toy story
