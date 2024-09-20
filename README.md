
# Content-Based Movie Recommendation System

This project is a **Content-Based Movie Recommendation System** that suggests movies similar to a selected movie. It uses TMDB metadata to generate tags for each movie, converts them into vectors, and calculates the cosine similarity between these vectors to recommend the top 5 similar movies.

An interactive **Streamlit** web interface allows users to select a movie and view recommended movies along with movie images, using the TMDb API.

----------

## Features

-   **Content-based filtering**: Recommends movies based on the content of the movie selected by the user.
-   **Cosine Similarity**: The system calculates similarity scores using cosine similarity to suggest movies that are most like the selected one.
-   **Interactive UI**: A user-friendly interface built with **Streamlit** allows users to easily select movies and view recommendations.
-   **TMDb API integration**: The system displays movie posters retrieved from the **TMDb API**.

----------

## Dataset

The movie metadata used for this recommendation system is from the [TMDB 5000 Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

To use this dataset in the project:

1.  Download the dataset from the [Kaggle link](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
2.  Save the dataset files (e.g., `tmdb_5000_movies.csv`) in the `datasets` directory of your project.
