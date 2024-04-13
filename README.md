# Movie Recommender System

## Overview

The Movie Recommender System using TF-IDF Vectorizer is a web application that recommends movies similar to the one selected by the user. It utilizes the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique to determine movie similarities based on textual features such as movie plots or descriptions. The application provides users with a selection box to either type or select a movie from a dropdown menu. Upon selecting a movie and clicking the "Show Recommendation" button, the system displays a list of recommended movies along with their posters.

## Project Description

The project involves the following components:

1. **Movie Selection**: Users can either type the name of a movie or select one from a dropdown menu containing a list of available movies.
2. **Recommendation Generation**: Upon selecting a movie and clicking the "Show Recommendation" button, the system generates recommendations based on the selected movie's similarity to other movies in the dataset using TF-IDF vectors.
3. **Display Recommendations**: The system displays the top five recommended movies along with their posters.

## Technologies Used

- **Streamlit**: An open-source Python library used for building interactive web applications.
- **Pickle**: Python's serialization module used for saving and loading data, including movie lists and TF-IDF matrices.
- **Requests**: A Python library used for making HTTP requests to fetch movie poster images from an external API (The Movie Database API).
- **CountVectorizer and Cosine Similarity**: model is trained using count vectorizer and predict using cosine similarity
## Usage

1. **Movie Selection**: Type the name of a movie or select one from the dropdown menu.
2. **Show Recommendation**: Click the "Show Recommendation" button to view recommended movies similar to the selected movie.
3. **Display Recommendations**: The system displays the top five recommended movies along with their posters.
