# Movie-Recommendor
Movie Recommendation System is a content-based recommendation system where the user inputs a movie and gets a list of movies related to it.
This project is implemented on the basis of correlation.
The correlation between the entered movie and other movies is calculated and sorted in a list which is output.


Note:
This is not a complete robust movie recommendation systems.
While there are many factors to be considerd in a movie like genres(action,comedy,adventerous,etc), in this project I have used user ratings as a parameter to consider for the recommendation.
The data set used in this project is attached. It is taken from movielens dataset.

Datasets:(downloaded from https://grouplens.org/datasets/movielens/)
1. itemid_movies: Each movie has an item id number related to it.This file contains all the movies with their corresponding item_id

2. userid_ratings: The users have given ratings to the movie. Every user has a user_id. This file has all the user_id along with item_id of the movie they have given ratings to and the timespan of the movies. 
