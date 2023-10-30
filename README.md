# Anime Recommendation System

**Features:**
- **Content-Based Recommendation:** Recommends similar anime titles using cosine similarity. Includes text preprocessing (lowercasing, tokenization, special character removal, stop word removal, and lemmatization).
- **Hybrid Recommendation:** Combines content similarity and average ratings to generate recommendations. Utilizes a weighted hybrid score (65% content-based, 35% ratings-based).

**Data Preprocessing:**
- Removes unnecessary columns from the dataset.
- Standardizes text formats by removing spaces, special characters, and specific words/patterns from synopses.
- Numerical columns are processed to remove commas and scaled using MinMaxScaler.

**Usage:**
- Allows users to input specific anime titles for both content-based and hybrid recommendations.
- Provides recommendations for a predefined list of anime titles.

**Libraries Used:**
- Pandas: For data manipulation and preprocessing.
- NLTK: For natural language processing tasks (tokenization, stop word removal, and lemmatization).
- Scikit-Learn: For TF-IDF vectorization, cosine similarity computation, and numerical feature scaling.
like tokenization, stop word removal, and lemmatization.
Scikit-Learn: For TF-IDF vectorization, cosine similarity computation, and numerical feature scaling.
