# Collaborative Filtering Recommendation System

This project implements a **User-Based Collaborative Filtering recommendation system** using the **MovieLens 100k dataset**. It predicts user ratings based on similar users' past preferences and evaluates its accuracy using **Root Mean Square Error (RMSE)**.

---

## 📌 Project Overview
- **Algorithm**: User-Based Collaborative Filtering
- **Dataset**: MovieLens 100k (100,000 ratings from 943 users on 1,682 movies)
- **Metric**: RMSE (Root Mean Square Error)
- **Library Used**: Surprise (scikit-surprise)

---

## 🚀 Features
✔ Uses **User-Based Collaborative Filtering**  
✔ Implements **Cosine Similarity** for recommendations  
✔ Trains on different dataset sizes for evaluation  
✔ Plots **training progress (RMSE reduction)**  

---

## 📂 Dataset: MovieLens 100k
The **MovieLens 100k** dataset consists of:
- 100,000 ratings from 943 users on 1,682 movies
- Ratings range from **1 to 5 stars**
- Includes timestamped user interactions
- Used for **recommender system training & evaluation**

---

## 🛠 Installation & Setup
### **1️⃣ Install Dependencies**
Make sure you have Python installed, then run:
```bash
pip install scikit-surprise matplotlib