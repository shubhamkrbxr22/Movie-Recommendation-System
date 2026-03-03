# 🎬 Movie Recommendation System

A Content-Based Movie Recommendation System built using **Python, Pandas, and NumPy**.  
This project analyzes user rating patterns and suggests similar movies using correlation-based similarity metrics.

---

## 🚀 Project Overview

This system recommends movies based on similarity scores computed from user ratings.  
It uses a subset of the **MovieLens dataset** to generate personalized movie suggestions.

The recommendation engine works by:
- Creating a user-movie rating matrix
- Computing correlation between movies
- Ranking movies based on similarity scores

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV Dataset (MovieLens subset)

---

## 📊 Dataset Information

The dataset contains:
- Movie IDs
- Movie Titles
- User Ratings

The system processes the dataset to create a pivot table (User vs Movie matrix) and computes similarity using Pearson correlation.

---

## ⚙️ System Workflow

1. Load dataset using Pandas
2. Clean and preprocess data
3. Create pivot table (user-movie matrix)
4. Compute correlation between movies
5. Sort movies based on similarity score
6. Return top recommended movies

---

## 🧠 Recommendation Logic

- Uses **Pandas corrwith()** to calculate similarity
- Filters movies with sufficient rating counts
- Sorts by correlation value
- Returns Top 4 most similar movies

---

## ▶️ How to Run the Project

1. Clone the repository:  git clone https://github.com/shubhamkrbxr22/Movie-Recommendation-System.git
2. Open the Jupyter Notebook: Movie Recommender System.ipynb

3. Run all cells

4. Enter a movie name to get recommendations

---

## 📌 Example Output

**Input:**
12 Angry Men (1957)

**Output:**
- Ulee's Gold (1997)
- Rear Window (1954)
- Seven Years in Tibet (1997)
- Clerks (1994)

---

## 🔮 Future Improvements

- Add GUI using Streamlit
- Deploy as Web Application
- Use Cosine Similarity
- Implement Collaborative Filtering
- Deploy on cloud (AWS / Render / Railway)

---

## 📂 Repository Structure
Movie-Recommendation-System/

├── Movie Recommender System.ipynb
├── dataset.csv
├── movieIdTitles.csv
├── MovieRecommendations.csv
└── README.md

---

## 👨‍💻 Author

**Shubham Kumar**  
GitHub: https://github.com/shubhamkrbxr22

---

⭐ If you found this project useful, consider giving it a star!
