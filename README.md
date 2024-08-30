# Movie Recommendation System

## Project Overview
This project implements a movie recommendation system that provides personalized movie suggestions based on user preferences. The system uses movie genres to compute similarity scores and recommend movies that align with the user's input.

## Dataset
The dataset used for this project is the [MovieLens 20M dataset](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?resource=download) from Kaggle. It contains information about movies, ratings, and user tags.

To use the dataset:
1. Download the dataset from [this link](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?resource=download).
2. Extract the contents of the zip file.
3. Place the CSV files (`movie.csv` and `rating.csv`) in the project directory.

Ensure that the files are placed in the correct directory as expected by the code.

## Features
- **Data Preprocessing**: Loads and cleans movie and rating data.
- **Feature Extraction**: Converts movie genres into a matrix of token counts using CountVectorizer.
- **Similarity Computation**: Calculates cosine similarity between movies to identify similar ones.
- **Recommendation Engine**: Provides movie recommendations based on user input.

## Contributors
This project was a collaborative effort between:
- [Arjun Chambarge](https://github.com/Arjun111223) - Data preprocessing, feature extraction, dataset management and testing
- [Jujhaar Singh Aidhen](https://github.com/JSA-Masterchief) - Similarity computation and recommendation logic
