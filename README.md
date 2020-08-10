# Movie recommendation system
## There are two modules :

1.Content Based Recommender Systems

2.Collaborative Filtering Based Recommender Systems



# Know the Data
Content based recommendations uses IMDB movie dataset "IMDB.csv" consisting of movie information on approx 5000 popular movies

Collaborative filtering uses movie lens dataset "ml-100k"


# Content based recommendation

Construction of content based feature vectors for items(movies).

Compute similarity between the items to recommend similar items.

# Collaborative Filtering

Using a python library for collaborative filtering called "surprise". It implements collaborative filtering model based methods like NMF,PMF,SVD and memory based collaborative filtering techniques such as KNN.

Collaborative filtering methods work with utility matrices containg user x item ratings. Every cell in the utility matrix corresponds to the rating given by user "i" to item to "j".

Building a collaborative system using SVD: Using the utility matrix the system predicts ratings for a new user-item pair and evaluates the performance using RMSE.

![https://github.com/aakashs11/MRS/blob/master/download.png]

# Metric Description

F1  a. The ratio of empty and total entries in the utility matrix.

Precision  b. Proportion of relevant results that are recommended.

MAE  c. The proportion of results classified correctly(both positive and negative).

Recall  d. Deviation between actual and predicted ratings.

Accuracy  e. Harmonic mean of precision and recall.

Sparsity   f. Proportion of recommended results that are relevant.

