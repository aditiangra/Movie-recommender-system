
# Content-Based-Movie-Recommender-System

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched from  <a href="https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv">Dataset</a>

# Theory and Overview

You can refer to the <a href="https://drive.google.com/file/d/1t0v4wclaxUw-3IN4SYRkgMrIPT_hZ2AA/view?usp=sharing">link</a> for overview of  project


# Architecture
![image](https://github.com/aditiangra/Movie-Recommender-System/assets/91600893/d85343b6-9d0b-417c-87a3-17bce5e8750a)



# Similarity Score :

How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.


# How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
 
![image](https://github.com/aditiangra/Movie-Recommender-System/assets/91600893/4410567d-5ece-4768-ae91-68faf6b29b05)

# Links
Dataset:https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
Preprocessing: https://drive.google.com/file/d/1t0v4wclaxUw-3IN4SYRkgMrIPT_hZ2AA/view?usp=sharing

















