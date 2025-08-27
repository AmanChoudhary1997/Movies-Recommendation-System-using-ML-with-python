![Image](https://github.com/user-attachments/assets/8451a100-323e-4813-b3d4-418644925725)

# 🎬 Movie Recommendation System

## 📌 Project Overview
The **Movie Recommendation System** suggests movies to users based on their input using **content-based filtering**. It uses **Natural Language Processing (NLP)** and **Cosine Similarity** to recommend movies similar to the one provided by the user.

This approach is widely used in platforms like **Netflix** and **Amazon Prime** to enhance user experience by providing personalized recommendations.

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Algorithm:** TF-IDF Vectorization + Cosine Similarity    

---

## 🔍 Business Use Case
Streaming services and OTT platforms use recommendation systems to:
- Increase **user engagement**  
- Provide **personalized suggestions**  
- Improve **customer retention**  

---

## 📂 Dataset
- Movie details such as:
  - **Title**
  - **Overview**
  - **Genres**
  - **Cast & Crew**
  - **Keywords**  
- Source: **TMDB Movie Dataset**  

---


### Steps:
1. **Data Collection**
   - Load the movie dataset containing details like title, genres, and overview.  

2. **Data Preprocessing**
   - Handle missing values  
   - Combine important text features (genres, keywords, cast, crew)  

3. **Feature Extraction**
   - Convert text data into numerical representation using **TF-IDF Vectorizer**  

4. **User Input**
   - Take a movie name as input from the user  

5. **Cosine Similarity**
   - Compute similarity between the input movie and all other movies  

6. **Recommendations**
   - Return a list of top similar movies based on similarity scores  

---

## ✅ How It Works
- User enters a movie name  
- The system finds similar movies based on text features  
- **Cosine Similarity** determines closeness between movies  

---

## ▶️ Example
**Input:** `Avatar`  
**Output:**  
- Guardians of the Galaxy  
- Star Wars: The Force Awakens  
- The Avengers  
- Star Trek  

---

