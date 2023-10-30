# Anime Recommendation System

This project implements an anime recommendation system using content-based and hybrid techniques. It processes anime data from a CSV file, conducts extensive text preprocessing on titles, themes, genres, and synopses, and utilizes TF-IDF vectorization for textual analysis.

**Features:**
- **Content-Based Recommendation:** Uses cosine similarity for anime suggestions based on textual features. Text preprocessing includes lowercasing, tokenization, special character removal, stop word removal, and lemmatization.
- **Hybrid Recommendation:** Combines content-based similarity and average ratings (65% content, 35% ratings) for personalized suggestions.

**Data Preprocessing:**
- Removes unnecessary columns.
- Standardizes text formats, removes spaces, special characters, and specific words/patterns from synopses.
- Numerical columns are processed to remove commas and scaled using MinMaxScaler.

**Usage:**
- Allows users to input specific anime titles for both content-based and hybrid recommendations.
- Provides recommendations for a predefined list of anime titles.

**Libraries Used:**
- **Pandas:** For data manipulation and preprocessing.
- **NLTK:** For tokenization, stop word removal, and lemmatization.
- **Scikit-Learn:** For TF-IDF vectorization, cosine similarity, and numerical scaling.
