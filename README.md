

# 🎬 Movie Recommendation System

![image](https://github.com/user-attachments/assets/d73ef469-540c-447f-93b8-0b66b0f3b159)
This project is a collaborative filtering-based movie recommendation engine developed to intelligently suggest movies to users based on their historical preferences. It utilizes the MovieLens dataset and applies data preprocessing, similarity computations, and evaluation techniques to build a personalized recommender.

---

## 👥 Group Members

- Rachael Nyawira  
- Winnie Odoyo  
- Austin Kanja  

---

## 📌 Problem Statement

In today's digital era, users are overwhelmed with thousands of movie options on streaming platforms. Without a reliable recommendation system, users spend excessive time searching for content, leading to poor engagement.

**Goal**: Build a system that analyzes past user ratings to recommend the top 5 movies a user is most likely to enjoy.

---

## 🎯 Business Understanding

Recommendation engines are crucial for content-based platforms like Netflix and Amazon Prime. A good recommender helps:

- Improve user satisfaction  
- Increase click-through rates  
- Prolong user engagement time  
- Boost content discoverability  

By analyzing movie rating patterns, this system aims to offer a personalized movie discovery experience.

---

## 🎓 Project Objectives

1. Analyze the MovieLens dataset to explore user behavior and movie trends.  
2. Clean and preprocess the data to prepare for modeling.  
3. Generate a user-item interaction matrix.  
4. Apply collaborative filtering (user and item-based) to recommend movies.  
5. Develop a function that returns the top 5 recommendations for any given user.  
6. Evaluate model effectiveness using qualitative insights.  
7. Present findings using clear and concise visualizations.

---

## 📊 Datasets Used

From the [MovieLens Latest Small Dataset](https://grouplens.org/datasets/movielens/latest/):

- `movies.csv` – movie IDs, titles, genres  
- `ratings.csv` – user ratings  
- `tags.csv` – user-generated tags  
- `links.csv` – external IDs (IMDB, TMDB)  

---

## 🛠️ Tools & Technologies

- **Language**: Python 3.x  
- **Libraries**:  
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib`, `seaborn` – data visualization  
  - `sklearn` – preprocessing and modeling  
- **Platform**: Jupyter Notebook  

---

## 🧹 Data Cleaning & Exploration

- Verified data types and null values  
- Checked for duplicates in all datasets  
- Merged datasets based on `movieId`  
- Explored:
  - Most rated movies  
  - Most common genres  
  - Rating distribution  
  - Correlation between ratings and movie popularity  

---

## 📊 Data Exploration Visuals

### 🔹 Top 10 Most Rated Movies

![image](https://github.com/user-attachments/assets/e4d9ea9c-cb57-4e2d-aa21-4e861565a9b9)



### 🔹 Distribution of Average Movie Ratings

![image](https://github.com/user-attachments/assets/1e97061e-74fa-4aec-80a1-5cc63d929ed7)


---

## 🧠 Conclusion and recommendations

1. User Engagement is Uneven
   * Insight: A small percentage of users account for a large portion of the ratings.
   * Business Takeaway: These are your power users — focus on retaining and rewarding them (e.g., personalized campaigns, early access to new releases).

3. Movie Popularity is Skewed
   * Insight: A handful of movies receive the majority of ratings.
   * Business Takeaway: These popular movies can be used to attract new users, but recommending only them may lead to redundancy and boredom. A recommendation system must balance popularity with diversity and novelty.

4. Ratings Tend to Be High (Positively Skewed)
    * Insight: Most ratings fall between 3 and 5, with very few ratings below 2.
    * Business Takeaway: Users may avoid rating movies they dislike. Consider implicit feedback signals (watch time, skips) alongside ratings for a more complete picture of preferences.

5. Genres Are Not Rated Equally
   * Insight: Certain genres like Drama, Comedy, and Action dominate the dataset.
   * Business Takeaway: These genres could be prioritized for acquisition or marketing, while less-rated genres (e.g., Documentary, War) could be niche recommendations to keep long-tail users engaged.

6. Rating Behavior Differs by User
   * Insight: Some users are harsh, others rate generously.
   * Business Takeaway: A personalized recommendation model must consider each user’s rating scale. This justifies using models like collaborative filtering or similarity-weighted predictions rather than raw
 

---
