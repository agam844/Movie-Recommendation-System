# Movie Recommendation System

This is a simple content-based movie recommender built using Python. It suggests similar movies based on movie metadata such as genres, keywords, cast, and crew.

## Features

- Recommends movies similar to the one you select
- Uses NLP to process movie descriptions
- Content-based filtering using cosine similarity
- Clean, interactive interface (compatible with Streamlit)

## How it Works

1. **Data Cleaning**: Processes movie metadata (genres, overview, keywords, etc.)
2. **Tag Generation**: Combines relevant text into a single "tag" for each movie
3. **Text Vectorization**: Uses `CountVectorizer` to convert tags into numerical form
4. **Similarity Calculation**: Computes cosine similarity between movies
5. **Recommendation**: Returns top 5 similar movies

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/agam844/Movie-Recommendation-System
   cd movie-recommendation-system
