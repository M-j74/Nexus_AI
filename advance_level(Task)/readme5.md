Part 3: Advanced Level (The Data Scientist) 
Focus: Solving complex problems with advanced techniques. 
Task 5: Building a Product Recommendation System 
 The "Why": To increase sales, GlobalMart wants to suggest products to users that they 
are likely to buy, just like Amazon and Netflix. 
 Description: Build a simple content-based recommendation system that suggests movies 
to a user based on movies they have previously liked. 
 Step-by-Step Guide: 
1. Feature Extraction: Use a dataset with movie genres, descriptions, or keywords. 
Convert this text data into a numerical matrix using TF-IDF Vectorizer. 
2. Similarity Calculation: Use Cosine Similarity to calculate the similarity 
between all movies based on their features. 
3. Build the Recommender Function: Create a Python function that takes a movie 
title as input and returns the top 5 most similar movies. 
 Suggested Dataset: TMDB 5000 Movie Dataset on Kaggle 
 Expected Outcome: A Python script or notebook with a function that can provide movie 
recommendations. Include an example of the recommendations for 2-3 different movies.
