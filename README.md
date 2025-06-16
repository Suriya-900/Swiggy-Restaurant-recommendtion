🍽️ Swiggy’s Restaurant Recommendation System using Streamlit
A machine learning-based recommendation system that suggests restaurants based on user preferences like city, cuisine, cost, and rating. Built with Python and Streamlit, the project demonstrates key skills in data preprocessing, clustering/similarity-based recommendations, and interactive app development.

📌 Project Overview
Goal:
Build a restaurant recommendation system using a CSV dataset and deploy it through a user-friendly Streamlit web application.

Tech Stack:

Python

Pandas, Scikit-learn

Streamlit

Clustering / Cosine Similarity

One-Hot Encoding

Pickle (for model persistence)

🎯 Problem Statement
The system recommends restaurants based on:

City

Rating

Cost

Cuisine preferences

It uses clustering or similarity-based techniques to find and display relevant restaurant options in a web interface.

🧠 Skills Gained
Data Cleaning & Preprocessing

One-Hot Encoding for categorical variables

Clustering / Cosine Similarity techniques

Streamlit App Development

Real-world application of Recommendation Systems

📂 Dataset
The dataset contains the following columns:

bash
Copy
Edit
['id', 'name', 'city', 'rating', 'rating_count', 'cost', 'cuisine',
 'lic_no', 'link', 'address', 'menu']
Feature Types:
Categorical: name, city, cuisine

Numerical: rating, rating_count, cost

🔧 Project Pipeline
1. Data Cleaning
Removed duplicates

Handled missing values

Output: cleaned_data.csv

2. Data Preprocessing
One-Hot Encoded categorical features

Saved encoder: encoder.pkl

Output: encoded_data.csv

3. Recommendation Engine
Used K-Means or Cosine Similarity

Processed data through encoded dataset

Mapped results back to cleaned_data.csv for readability

4. Streamlit App
User Input: City, Cuisine, Cost, Rating

Backend: Generates recommendations from encoded dataset

Frontend: Displays top restaurant matches with details

💼 Business Use Cases
Personalized Suggestions: Match user preferences with relevant restaurants

Enhanced Customer Experience: Quick decision-making with tailored options

Market Insights: Analyze user trends and food preferences

Business Optimization: Help restaurants align offerings with popular demand

✅ Results
Cleaned & processed data stored as:

cleaned_data.csv

encoded_data.csv

encoder.pkl

Interactive Streamlit App built for real-time recommendations

Scalable recommendation logic using clustering/similarity
