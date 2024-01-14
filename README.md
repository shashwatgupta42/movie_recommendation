# Movie Recommendation (collaborative filtering)

In this project, I apply collaborative filtering (from scratch) for movie recommendations. The dataset contains 100836 ratings by 610 users across 9742 movies. 

The model has no information about the movies except user ratings. The attempt is to extract valuable information about the movies and the users using such limited data.
Fundamentally, this project aims to predict user rating for a movie that the user has not yet rated.

Using the derived information, we will be able to perform the following tasks - 
1) Predict movies for a given user
2) Predict how a user will rate a given movie
3) Measure the difference between two movies
4) Measure the difference between two users
5) Predict movies similar to a given movie

Dataset Source - https://grouplens.org/datasets/movielens/latest/ <br>
About the dataset - https://files.grouplens.org/datasets/movielens/ml-latest-small-README.html <br>

### No machine learning library or autodiff has been used. The implementation of collaborative filtering is from scratch.

There are 207290 parameters in this project and all have been trained using Adaptive Moment Estimation (Adam) in a vectorized manner with regularization.

Content - 

- main.ipynb - main jupyter notebook
- ml-latest-small - dataset folder
- trained_parameters - folder containing trained parameter (binary file)

