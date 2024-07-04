# Happy-intern-project1

Description:
A movie recommendation system that uses the MovieLens 100k dataset to suggest movies to users based on their preferences.

Features:
Data Handling: Loads and preprocesses movie ratings and titles.
Models: Embeds user IDs and movie titles into a shared 64-dimensional space.
Retrieval Task: Uses TensorFlow Recommenders to find the most relevant movies for users.
Training: Optimized using Adagrad and evaluates with FactorizedTopK metrics.
Recommendations: Provides movie recommendations for a given user using a brute-force search approach.
