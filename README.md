Movie Recommendation System

This project is a Movie Recommendation System developed using Python.
The system suggests movies that are similar to a selected movie by analyzing movie details such as genres, overview, keywords, cast, and crew.
By comparing these features, the system identifies similarities between movies and recommends the most relevant ones. 
This project demonstrates the use of data preprocessing, text analysis, and similarity measurement to build an intelligent recommendation system.
This is a content-based recommender system.

Objective:

To recommend similar movies based on movie details using Python.

Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

Dataset

The dataset contains information about movies such as:
- Title
- Genres
- id
- Overview
- Keywords
- Cast
- Crew

The data was cleaned and preprocessed before building the recommendation system.

Data cleaning involves checking for missing values using isnull() and removing
duplicate entries using duplicated() to ensure accurate recommendations.

Data Analysis & Interpretation

-The provided data set includes both the movies and credits data set.
-The movies data set consists of 4803 rows and 20 columns.The column includes budget,genres,homepage,id,keywords,
 original_language,original_title,overview,popularity,production_companies,production_countries,release_date,revenue,
 runtime,spoken_languages,status,tagline,title,vote_average and vote_count.And also credits data set consists of  4803
 rows and 4 columns.The column includes movie_id,title,cast and crew.
-Two datasets, movies and credits, were merged using the movie title to create a single dataset with 23 columns.
 From this combined dataset, only 7 important columns—title, genres, overview, keywords, id, cast, and crew—were selected for analysis. 
 These features are used to compare movies and generate recommendations based on similarity.
-The processed movie details were converted into numerical form so that similarity between movies could be calculated.
 This allows the system to compare movies effectively.
-Movies with similar details show higher similarity.
 When a movie is selected, the system finds other movies with similar characteristics and recommends them.
 This helps users discover movies related to their interests.

Output
