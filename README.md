
# Movie Recommendation System

Movies Recommendation Systems can be of two types
- Content based
- Collaborative

**Content-Based Filtering:**
This filtration strategy is based on the data provided about the items. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences.
For example, if a user likes movies such as ‘The Prestige’ then we can recommend him the movies of ‘Christian Bale’ or movies with the genre ‘Thriller’ or maybe even movies directed by ‘Christopher Nolan’.So what happens here the recommendation system checks the past preferences of the user and find the film “The Prestige”, then tries to find similar movies to that using the information available in the database such as the lead actors, the director, genre of the film, production house, etc and based on this information find movies similar to “The Prestige”.



**Collaborative Filtering:**
This filtration strategy is based on the combination of the user’s behavior and comparing and contrasting that with other users’ behavior in the database. The history of all users plays an important role in this algorithm. The main difference between content-based filtering and collaborative filtering that in the latter, the interaction of all users with the items influences the recommendation algorithm while for content-based filtering only the concerned user’s data is taken into account.
There are multiple ways to implement collaborative filtering but the main concept to be grasped is that in collaborative filtering multiple user’s data influences the outcome of the recommendation. and doesn’t depend on only one user’s data for modeling.




![](https://github.com/arshadali12/Movie-Recommender-System/blob/main/Screenshots/recommender-types.PNG)

**In this project I have made Content based Movie Recommender System**

### Dataset Used
I have used TMDB 5000 Movies Dataset from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/code?select=tmdb_5000_movies.csv) 

### Predictions
I have used two vectorization techniques in this project.


![](https://github.com/arshadali12/Movie-Recommender-System/blob/main/Screenshots/preds.PNG)

