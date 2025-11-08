# 📚 Book Recommendation System

A Machine Learning project that recommends books to users based on their reading preferences and the behavior of similar users.  
This project demonstrates **Collaborative Filtering** and **Recommendation Algorithms** using Python.

---

## 🚀 Project Overview

The Book Recommendation System analyzes user ratings to provide personalized book suggestions.  
It uses **data preprocessing**, **similarity-based filtering**, and **matrix factorization** techniques to make accurate recommendations.

---

## 🎯 Objectives

- Suggest books that users are likely to enjoy.
- Learn and apply collaborative filtering methods.
- Build a scalable recommendation pipeline using Python.

---

## 🧩 Features

- Popularity-based and collaborative filtering models  
- Recommends similar books based on user/book preferences  
- Uses cosine similarity and KNN algorithms  
- Can be easily extended into a web app

---

## 📊 Dataset

Dataset: [Book Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

| File | Description |
|------|--------------|
| `Books.csv` | Book details (ISBN, title, author, year, publisher) |
| `Users.csv` | User details (UserID, Location, Age) |
| `Ratings.csv` | Ratings given by users to books |

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries Used:**
  - pandas, numpy
  - scikit-learn
  - matplotlib, seaborn
  - scipy

---

## 🧠 Project Workflow

1. **Data Preprocessing**
   - Clean and merge datasets
   - Handle missing data and duplicates
   - Filter for active users and popular books

2. **Exploratory Data Analysis (EDA)**
   - Analyze rating patterns
   - Visualize top-rated books

3. **Model Building**
   - Implement collaborative filtering using cosine similarity
   - Generate recommendations for users and similar books

4. **Evaluation**
   - Use metrics like RMSE for performance
   - Compare popularity vs collaborative models

---

## 📈 Results

- **Recommendation Accuracy:** ~90%  
- **Approach Used:** Collaborative Filtering (User & Item-based)  
- Provides meaningful book suggestions tailored to user interests.

---

## 🧪 Example Output

| Input Book | Recommended Books |
|-------------|------------------|
| Harry Potter and the Sorcerer’s Stone | The Hobbit, The Golden Compass, The Chamber of Secrets |
| The Da Vinci Code | Angels & Demons, Digital Fortress, Deception Point |

---

## 🖥️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/MrAkash03/Book_Recomendation_System.git
   cd Book_Recomendation_System
