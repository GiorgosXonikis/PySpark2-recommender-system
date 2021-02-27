## Movies Recommender System with PySpark 2

This project was part of my MSc thesis in Big Data Analytics using Hadoop.

The goal is to create a movies recommender system using the distributed proccesing power of PySpark 2.

The ML algorith that is used is Collaborative Filtering with ALS (AlternatingLeastSquares).

### About this Dataset
The datasets describe ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies.
Content

No demographic information is included. Each user is represented by an id, and no other information is provided.

The data were used are:


rating.csv that contains ratings of movies by users:

    userId

    movieId

    rating

    timestamp

movie.csv that contains movie information:

    movieId

    title

    genres
    


Acknowledgements

The original datasets can be found here: https://grouplens.org/datasets/movielens/. To acknowledge use of the dataset in publications, please cite the following paper:

F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. DOI=http://dx.doi.org/10.1145/2827872
