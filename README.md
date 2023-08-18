# Movie Recommendation Engine Development in Apache Spark
In this project, I built a simple movie recommendation engine using Alternating Least Squares (ALS) algorithm in collaborative filtering with Spark ML on [MovieLens movie rating dataset](https://grouplens.org/datasets/movielens/latest/). The idea behind collaborative filtering is that if rating data from many users on many movies is available, a user’s ratings can be predicted for the movies not watched yet, then giving some recommendations. We can also find some similar movies for a given movie. We also use [The Movie Database (TMdb) API](https://www.themoviedb.org/documentation/api) to dislay recommended movie posters to the user.

This dataset contains metadata for 27,000,000 ratings and 1,100,000 tag applications applied to 58,000 movies by 280,000 users listed in the Full MovieLens Dataset last updated on Sep 2018. Includes tag genome data with 14 million relevance scores across 1,100 tags.

The project contains:
* Built a data ETL pipeline to analyze 110K+ movie rating records, enabling OLAP with Spark SQL.
* Implemented the Alternative Least Square model for personalized movie recommendations and user-based approaches for cold-start problems.
* Conducted hyper-parameter tuning via Spark ML cross-evaluation toolbox.
* Enhanced user experience by displaying recommended movie posters through The Movie Database API.
