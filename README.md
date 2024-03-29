﻿# Movie-recommendation-model

# Introduction
This project aims to build a movie recommendation engine using machine learning techniques. The system takes the user's movie preferences and recommends new movies that the user is likely to enjoy. The movies are recommended based on the content of the movie you entered or selected. The main parameters that are considered for the recommendations are the genre, director, and top 3 casts. The details of the movies, such as title, genre, runtime, rating, poster, casts, etc., are fetched from TMDB.

# Technical Requirements
Python 3.x
Jupyter Notebook or similar IDE
Libraries: pandas, numpy, scikit-learn, scipy, matplotlib,TMDB API wrapper, nltk, streamlit

# Data Collection
The movie dataset used for building the recommendation engine was obtained from Wikipedia and The Movie Database (TMDB) API. This API provides access to a wealth of information about movies, including their ratings, genres, cast, and other attributes. The data was fetched using the TMDB API and stored in a local database for processing.The dataset includes movies released till 2019.


# Preprocessing
The movie dataset was preprocessed to remove any missing values, duplicates, and irrelevant information. The preprocessed dataset was then used to build the recommendation engine. All the dataset and features were alligned according to the need of the model into the final preprocessing file.

# Content-Based Filtering
Content-based filtering is a technique used to make recommendations based on the attributes of the items being recommended. In this project, the recommendation engine uses a content-based filtering approach to recommend movies based on the genre, director, cast, and other attributes of the movies.

# Evaluation
The recommendation engine was evaluated using the Cosine Similarity metric. Cosine Similarity measures the cosine of the angle between two non-zero vectors and is used to determine the similarity between two items. The higher the cosine similarity score, the higher the similarity between the two items.

# Deployment
The recommendation engine has been deployed as a web application using the Streamlit framework. The user interface of the application allows users to input their movie preferences and receive recommendations.

# Conclusion
In conclusion, this project demonstrates the feasibility of building a movie recommendation engine using machine learning techniques. The recommendation engine provides accurate and personalized movie recommendations based on the preferences of the user. Additionally, using the TMDB dataset obtained from Kaggle can further enhance the recommendations: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
