📚 Book Recommendation System
🚀 Overview
This is a Book Recommendation System built using Flask (backend framework), scikit-learn, and Python (Jupyter Notebook). It provides:
1️⃣ Top 80 Books Based on Popularity Filtering & Indexing
2️⃣ Personalized Book Recommendations Based on User Preferences

The dataset is sourced from a Kaggle competition. The UI is designed with HTML, CSS (Bootstrap for automatic color selection), and Flask for backend integration.

🛠️ Tech Stack
Backend: Flask (Python Web Framework)

Machine Learning: scikit-learn, Pandas, NumPy

Model Storage: Pickle (to save trained models)

Frontend: HTML, CSS (Bootstrap for styling)

Notebook: Jupyter Notebook (for development and testing)

🔍 How It Works
1️⃣ Data Processing & Popularity Filtering
The dataset is preprocessed to filter the top 80 books based on popularity (ratings, reviews, or interactions).
Indexing is applied to retrieve books efficiently.

2️⃣ Personalized Recommendations
The system uses collaborative filtering and content-based filtering to suggest books based on user preferences (e.g., past interactions, book genres)
scikit-learn models are trained and saved using Pickle for efficient retrieval.

3️⃣ Flask Backend & UI Integration
Flask handles user requests, processes recommendations, and serves responses to the UI.
The HTML frontend dynamically displays recommended books.
CSS (Bootstrap) ensures an auto-adjusting color theme for an appealing interface.

🎯 How to Run Locally
🔹 Prerequisites
Python 3.12.x, Jupyter Notebook
Flask
scikit-learn, Pandas, NumPy

📌 Future Enhancements
🔹 Implement Hybrid Filtering for better recommendations
🔹 Add User Authentication & Reviews
🔹 Improve UI/UX with more customization
