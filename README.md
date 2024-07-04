# Happy-intern-project1

### Recommendation Systems Implemented

### Recommendation System 1: Collaborative Model

## Description:
A movie recommendation system that uses the MovieLens 100k dataset to suggest movies to users based on their preferences.

#### Features:
- **Data Handling:** Loads and preprocesses movie ratings and titles.
- **Models:** Embeds user IDs and movie titles into a shared 64-dimensional space.
- **Retrieval Task:** Uses TensorFlow Recommenders to find the most relevant movies for users.
- **Training:** Optimized using Adagrad and evaluates with FactorizedTopK metrics.
- **Recommendations:** Provides movie recommendations for a given user using a brute-force search approach.

### Recommendation System 2: 
### Collaborative Filtering using Matrix Factorization

## Description
A movie recommendation system using matrix factorization and TensorFlow Recommenders, based on the MovieLens 100k dataset. This project predicts user ratings for movies and provides recommendations.

## Features

- **Data Loading:** Utilizes the MovieLens 100k dataset for ratings and movie titles.
- **Matrix Factorization Model:** Incorporates user and movie embeddings along with a rating prediction model.
- **Training:** Uses Mean Squared Error for loss calculation and Adagrad optimizer.
- **Recommendations:** Retrieves and displays top movie recommendations for a given user.

### Recommendation System 3: 
### Hybrid Model (Collaborative Filtering + Content-Based Filtering)

## Description
A hybrid movie recommendation system using TensorFlow Recommenders with matrix factorization and TensorFlow's deep learning capabilities. This project predicts user ratings and provides movie recommendations based on user preferences.

## Features

- **Data Loading:** Uses the MovieLens 100k dataset for ratings and movie titles.
- **Hybrid Model:** Combines user and movie embeddings with a dense rating prediction model.
- **Training:** Optimized with the Adagrad optimizer and Mean Squared Error loss.
- **Recommendations:** Retrieves top movie recommendations for a specified user.

