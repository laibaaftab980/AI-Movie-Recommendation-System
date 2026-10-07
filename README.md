# AI Movie Recommendation System

## Project Overview

This project is an **AI-based Movie Recommendation System** developed using Python and the MovieLens dataset.

The system uses **Collaborative Filtering** to recommend movies that have similar user rating patterns. When a user selects a movie, the system calculates the correlation between that movie and other movies and displays the Top 10 recommendations.

## Features

* MovieLens dataset integration
* User-Movie Rating Matrix
* Collaborative Filtering
* Movie similarity calculation using correlation
* Top 10 movie recommendations
* Similarity score visualization
* Recommended movies with genres
* Google Colab implementation

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* MovieLens Dataset
* Collaborative Filtering

## Dataset

The project uses the **MovieLens Latest Small Dataset** provided by GroupLens Research.

Dataset Source:
https://grouplens.org/datasets/movielens/

The dataset is automatically downloaded through the Google Colab notebook.

## How It Works

1. Download the MovieLens dataset.
2. Load the ratings and movies data.
3. Merge the datasets using `movieId`.
4. Create a User-Movie Rating Matrix.
5. Select a movie.
6. Calculate correlations between the selected movie and other movies.
7. Filter movies with sufficient rating data.
8. Sort movies according to similarity scores.
9. Display the Top 10 recommended movies.
10. Visualize the recommendation scores using a bar chart.

## Project Files

* `Movie_Recommendation_System.ipynb` — Complete Google Colab notebook containing the project implementation.

## Running the Project

The notebook can be opened in **Google Colab** and executed cell by cell.

The MovieLens dataset is automatically downloaded by the notebook, so the dataset files do not need to be uploaded separately.

## Output

The system generates:

* Recommended movies
* Similarity/correlation scores
* Recommendation graph
* Recommended movies with genres

## Conclusion

This project demonstrates how Artificial Intelligence and collaborative filtering techniques can be used to build a simple movie recommendation system based on user rating patterns.
