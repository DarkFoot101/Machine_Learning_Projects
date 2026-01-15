# 📚 Book Recommendation System

## 🚀 Overview

This project implements a **Book Recommendation System** that provides both **popularity-based recommendations** and **personalized book suggestions** using collaborative filtering techniques.  
The system is built with **Flask** for backend integration and **scikit-learn** for machine learning, with development and experimentation performed in **Jupyter Notebook**.

The dataset used for training and evaluation is sourced from a **Kaggle competition**.

---

## ✨ Features

- **📈 Popularity-Based Recommendations**  
  Displays the **Top 80 most popular books** based on user interactions such as ratings and reviews.

- **🎯 Personalized Book Recommendations**  
  Suggests books tailored to user preferences using **collaborative filtering and content-based techniques**.

- **🌐 Web-Based Interface**  
  Interactive UI built with **HTML, CSS, and Bootstrap**, integrated with a Flask backend.

---

## 🛠️ Tech Stack

| Component | Technologies |
|---------|--------------|
| **Backend** | Flask (Python Web Framework) |
| **Machine Learning** | scikit-learn |
| **Data Processing** | Pandas, NumPy |
| **Model Persistence** | Pickle |
| **Frontend** | HTML, CSS, Bootstrap |
| **Development** | Jupyter Notebook |

---

## 🔍 How It Works

### 1️⃣ Data Processing & Popularity Filtering
- The dataset is preprocessed to clean and structure user–book interaction data.
- Books are ranked based on popularity metrics such as **ratings, reviews, and interaction counts**.
- The **Top 80 books** are selected using indexing for efficient retrieval.

---

### 2️⃣ Personalized Recommendations
- Uses **collaborative filtering** and **content-based filtering** to recommend books.
- Suggestions are generated based on user preferences such as:
  - Past interactions
  - Book genres
- Trained models are serialized using **Pickle** for fast loading during inference.

---

### 3️⃣ Flask Backend & UI Integration
- Flask handles incoming user requests and serves recommendation results.
- The frontend dynamically displays recommended books.
- **Bootstrap** ensures a responsive layout with an automatically adjusting color theme.

---

## ▶️ How to Run Locally

### 🔹 Prerequisites
- Python **3.12.x**
- Jupyter Notebook
- Flask
- scikit-learn, Pandas, NumPy

### 🔹 Steps

git clone https://github.com/your-username/book-recommendation-system.git
cd book-recommendation-system
pip install -r requirements.txt
python app.py

📌 Future Enhancements
Implement hybrid filtering for improved recommendation quality

Add user authentication and review submission

Enhance UI/UX customization and personalization

📃 License
This project is open-source and available under the MIT License.

A practical implementation of recommendation systems combining data preprocessing, similarity-based learning, and web application development.


*DATASET* - [https://www.kaggle.com/datasets/arash...](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)
