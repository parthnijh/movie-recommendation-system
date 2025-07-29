# Movie Recommendation System

This is a content-based movie recommendation system built using Python and scikit-learn.  
It uses cosine similarity to recommend movies based on genres, keywords, and cast features.

## Features

- Content-based filtering  
- TF-IDF Vectorizer for text features  
- Cosine similarity for recommendation  
- Simple and interpretable approach  

## How It Works

1. Dataset contains movie information (genres, cast, keywords, etc.)  
2. Relevant features are combined into a single string  
3. TF-IDF is applied to transform text to vectors  
4. Cosine similarity is used to calculate similarity between movies  
5. User selects a movie and receives top N similar movie recommendations  

## Libraries Used

- pandas  
- scikit-learn  

## How to Run

1. Clone this repository or download the notebook  
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab  
3. Run all cells  
4. Enter a movie name and get recommendations  
