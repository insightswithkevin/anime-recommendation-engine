# 🎥 Hybrid Anime Recommendation System

## 🚀 Project Overview

This project develops a hybrid recommendation engine tailored for the **MyAnimeList (MAL)** platform, combining **item-based collaborative filtering** with **content-based genre analysis**. The goal is to generate personalized anime recommendations by leveraging both user rating patterns and anime genre similarities.

Implemented in **Python**, this project focuses on practical recommendation algorithms, interpretable evaluation, and real-world applicability in streaming and entertainment platforms.

---

## 🎯 Objectives

### 1. **How consistent are user ratings and what patterns emerge?**

- Conducted exploratory data analysis on user rating behavior  
- Measured rating entropy to identify consistent vs. inconsistent raters  
- Insights guide preprocessing for recommendation accuracy  

---

### 2. **How effective is item-based collaborative filtering for anime recommendations?**

- Focused on item-item similarity via cosine similarity on centered ratings  
- Compared recommended anime to user watch history (case study: user `k3v1n`)  
- Highlighted strengths like stable catalog recommendations and sequel detection  

---

### 3. **Can recommendations be improved by blending genre similarity with collaborative filtering?**

- Incorporated Jaccard similarity on anime genres for content-based context  
- Developed a weighted hybrid model combining item-based and genre similarities  
- Demonstrated enhanced recommendations addressing cold-start and niche content  

---

## 🔧 Tools & Libraries

- `pandas`, `numpy` – Data manipulation and numerical operations  
- `scikit-learn` – Similarity computations and evaluation metrics  
- `scipy` – Distance metrics for content similarity  
- `matplotlib`, `seaborn` – Visualization of data distributions and results  

---

## 📈 Key Takeaways

- User rating consistency impacts recommendation quality and model robustness  
- Item-based collaborative filtering effectively captures stable, related content (sequels, similar titles)  
- Hybrid models improve semantic relevance and mitigate data sparsity challenges  
- Personalized recommendations for real user profiles enhance business value  

---

## 🧠 Learning Highlights

- Applied both collaborative and content-based filtering in a hybrid framework  
- Explored evaluation metrics for recommendation accuracy (e.g., RMSE, Precision@k)  
- Gained hands-on experience with real-world, large-scale user-item data  
- Developed transferable skills for entertainment industry and streaming service analytics  

---

## 📁 Dataset Info

- 📦 Source: [MyAnimeList User Ratings Dataset by Andrew Gatchalian on Kaggle](https://www.kaggle.com/datasets/andrewgatchalian/myanimelist-user-ratings)
- 💡 Data includes tens of thousands of user ratings and genre annotations across thousands of anime titles
