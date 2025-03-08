# Movie Recommendation System

## Overview
This project focuses on building a movie recommendation system using machine learning techniques. The system suggests movies to users based on their preferences and past interactions. It leverages collaborative filtering and content-based filtering approaches to generate personalized recommendations.

## Dataset https://drive.google.com/file/d/1UPbJTvSugtJUhOoxuvF4Ng10yIeqkkk0/view?usp=sharing
The dataset consists of movie metadata, user ratings, and interactions. It includes features such as:
- Movie titles, genres, and descriptions
- User ratings and reviews
- Movie release years and popularity

## Feature Engineering
Feature engineering was performed to improve recommendation accuracy. This includes:
- Text vectorization for movie descriptions (TF-IDF, CountVectorizer, Word2Vec)
- Encoding categorical features such as genres and directors
- User-item interaction matrix construction
- Similarity computation using cosine similarity and Pearson correlation

## Recommendation Approaches
The following approaches were implemented:
- **Content-Based Filtering**: Recommends movies similar to those a user has liked based on metadata.
- **Collaborative Filtering**:
  - User-Based Filtering: Finds users with similar preferences and recommends movies they liked.
  - Item-Based Filtering: Finds similar movies based on user interactions.
- **Hybrid Approaches**: Combines content-based and collaborative filtering for better results.

## Model Evaluation
The recommendation models were evaluated using:
- Mean Squared Error (MSE)
- Precision and Recall
- Normalized Discounted Cumulative Gain (NDCG)
- Mean Average Precision (MAP)

## Requirements
To run this project, install the necessary dependencies:
```bash
pip install numpy pandas scikit-learn surprise nltk tensorflow
```

## How to Run
1. Load the dataset.
2. Perform data preprocessing and feature engineering.
3. Train and evaluate recommendation models.
4. Generate movie recommendations based on user preferences.

## Conclusion
This project demonstrates the use of machine learning for building a movie recommendation system. Future improvements could include deep learning approaches such as neural collaborative filtering or reinforcement learning for more accurate recommendations.

## Author
Gunjan Mishra

