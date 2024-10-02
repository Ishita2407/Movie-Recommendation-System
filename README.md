# Movie-Recommendation-System
This project is a content-based movie recommendation system that suggests 5 similar movies based on a user-selected input. It processes a database of over 5000 movies to provide personalized movie recommendations.

# Features
- Recommends 5 similar movies based on user selection.
- Uses Bag-of-Words for text vectorization.
- Employs cosine similarity to identify movie similarities.
- Average recommendation speed of 34 seconds.
  
# How It Works
- Data Processing: A dataset of 5000+ movies is processed.
- Text Vectorization: The Bag-of-Words technique is applied to movie overviews and metadata.
- Cosine Similarity: Movie similarities are calculated based on text vectors.
- Recommendations: When a user selects a movie, the system suggests 5 similar movies.
  
https://github.com/Ishita2407/Movie-Recommendation-System/assets/91796142/5e1f6da8-1c90-4ff2-af37-bb49f4406519

# Technologies Used
- Python: Core programming language.
- Pandas: For data manipulation.
- Scikit-learn: For Bag-of-Words and cosine similarity computation.
- Streamlit: For building the user interface (optional).
  
## Dataset
The dataset contains over 5000 movie entries with features like:
1. Movie title
2. Overview
3. Genres
4. Cast and crew

## Future Enhancements
- Integrating additional filtering options such as genre, director, or actors.
- Improving recommendation speed.
- Enhancing the user interface with a more dynamic experience.

