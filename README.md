# MovieLens-Recommendation-Systems

🎬 Movie Recommendation System
📌 Overview
This project builds a Movie Recommendation System using the MovieLens 100K dataset.
It uses a hybrid approach combining item-based collaborative filtering and machine learning models to predict how a user would rate unseen movies, then recommends the top 5 most relevant titles.


🧑‍🤝‍🧑 Group Members
Rachael Nyawira

Winnie Odoyo

Austin Kanja

🚀 Objectives
Predict user ratings for movies they haven’t seen using:

Decision Tree Regressor

KNN Regressor

Generate personalized top-5 movie recommendations.

Evaluate and compare model performance.

Derive business insights based on prediction accuracy.

🧠 Methodology
Data Preprocessing

Used ratings.csv and movies.csv from MovieLens.

Created a user-item matrix and computed item-item cosine similarity.

Engineered a sim_weighted_rating feature based on a user’s past ratings of similar movies.

Modeling

Trained Decision Tree and KNN regressors on the similarity-weighted feature to predict movie ratings.

Used the trained models to generate top-5 personalized recommendations for each user.

Evaluation

RMSE and R² used to evaluate model accuracy.

Visualized metrics for comparison.

Recommendation Function

Custom function built to return top 5 movies (movie ID, title, predicted rating) for any user.

📊 Results
Model	RMSE ↓	R² ↑
Decision Tree	✅ Lower	✅ Higher
KNN Regressor	Higher	Lower

Decision Tree outperformed KNN, making it the preferred model for this task.

💼 Business Insights
More accurate predictions from the Decision Tree model lead to better recommendations, improving user satisfaction and retention.

Enhanced personalization translates to longer engagement time, higher ad revenue, and increased subscription conversion.

Investing in robust recommender systems strengthens the platform’s competitive edge in the streaming industry.

🛠️ Technologies Used
Python (Pandas, NumPy, Scikit-learn)

Seaborn & Matplotlib for visualization

Jupyter Notebook for development

📁 Files

File	Description

ratings.csv	User ratings data from MovieLens

movies.csv	Movie metadata (ID and title)

recommendation.py	Core functions for generating recommendations

visualize_metrics.py	Visualization of RMSE and R²


👥 Group Credits
This project was completed by:

Rachael Nyawira

Winnie Odoyo

Austin Kanja
