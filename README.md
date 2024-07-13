# Project Name 

## Movie Recommender System

A web application that recommends movies based on a user's favorite movie. The application uses Streamlit for the web interface and The Movie Database (TMDb) API to fetch movie posters.

## Features

- Recommends similar movies based on a selected movie.
- Displays movie posters and titles for the recommended movies.
- Uses a pre-trained similarity model for recommendations.

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```
2. Open your web browser and go to `http://localhost:8501`.
3. Select your favorite movie from the dropdown and click the "Recommend" button to get movie recommendations.

## Code Overview

### `app.py`

The main file that contains the Streamlit application. It includes the following functions:

- `fetch_poster(movie_id)`: Fetches the poster for a given movie ID using the TMDb API.
- `recommend(movie)`: Recommends movies similar to the given movie and fetches their posters.
- Streamlit components for displaying the user interface.

### Pre-trained Models

- `similarity.pkl`: The pre-trained similarity matrix.
- `movies.pkl`: The DataFrame containing movie titles and IDs.

## Dependencies

- streamlit
- requests
- pandas
- pickle

!! Make sure to install this dependencies on streamlit module !!
