# 🎬 Movie Recommendation System

This project implements a **collaborative filtering-based movie recommendation system** using the **MovieLens dataset** and the **Surprise library** in Python.

## 📌 Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Implementation Details](#implementation-details)
6. [Results](#results)
7. [Future Improvements](#future-improvements)
8. [License](#license)

---

## 📌 Overview
This recommendation system uses **collaborative filtering** to predict movie ratings and suggest movies to users.  
It is built using:
- **Python**
- **Surprise Library** (for collaborative filtering)
- **MovieLens Dataset** (for training and testing)

The system is implemented in **Google Colab** and can be easily adapted for other datasets.

---

## 📂 Dataset
The dataset used is the **MovieLens Small Dataset**, which contains:
- **100,000 ratings** from **600 users** on **9,000 movies**.
- **Movies file (`movies.csv`)**: Contains movie titles and genres.
- **Ratings file (`ratings.csv`)**: Contains user IDs, movie IDs, and ratings.

📥 **Download Dataset** → [MovieLens](https://grouplens.org/datasets/movielens/)

---

## ⚙️ Installation
To run this project, install the required libraries:
```bash
pip install pandas numpy scikit-surprise matplotlib seaborn
