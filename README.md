# Anime-Recommendation-System
This project implements an anime recommendation system using content-based and hybrid recommendation techniques. The system processes anime data from a CSV file, performs extensive text preprocessing on anime titles, themes, genres, and synopses, and utilizes TF-IDF vectorization for textual feature representation.

Features:

Content-Based Recommendation: Utilizes cosine similarity to recommend anime titles similar to a given input title based on textual features. Text preprocessing includes lowercasing, tokenization, special character removal, stop word removal, and lemmatization.
Hybrid Recommendation: Combines content-based similarity and average ratings to generate hybrid scores for anime titles. The hybrid score is calculated as a weighted sum of content-based similarity (65%) and average ratings (35%).
Data Preprocessing:

Removes unnecessary columns from the dataset.
Standardizes text formats by removing spaces and special characters, replacing commas, and removing specific words and patterns from synopses.
Numerical columns are preprocessed to remove commas and scaled using MinMaxScaler.
Usage:

The system allows users to input specific anime titles and get both content-based and hybrid recommendations.
Provides recommendations for a predefined list of anime titles.
Libraries Used:

Pandas: For data manipulation and preprocessing.
NLTK: For natural language processing tasks like tokenization, stop word removal, and lemmatization.
Scikit-Learn: For TF-IDF vectorization, cosine similarity computation, and numerical feature scaling.
