# Movie Recommendation System

A movie recommendation system is a tool designed to predict or filter items (movies) according to a user's preferences or the behavior of people with similar interests. In simple terms, it aims to suggest movies that you might like based on your own viewing history or the preferences of users with similar tastes.

## Project Overview

In this project, I built a movie recommendation system using natural language processing (NLP) concepts to analyze movie-related data. The system uses a text vectorization technique called **Bag of Words** and applies **Euclidean distance** to calculate similarities between different movies.

## Tools & Libraries Used

- **Numpy**: For numerical computations
- **Pandas**: For data manipulation and analysis
- **Pickle**: For saving and loading trained models
- **Requests**: To handle HTTP requests
- **NLTK (Natural Language Toolkit)**: For natural language processing and text analysis
- **Streamlit**: For building the web application to showcase the recommendation system

## Methodology

- **Text Vectorization**: I used the **Bag of Words** technique to convert movie descriptions into vectors for analysis.
- **Similarity Calculation**: To find similar movies, I applied **Euclidean distance** to the vectorized text data.
  
## Web Application

A web app was built using **Streamlit** to allow users to interact with the recommendation system. Users can input a movie, and the app will recommend similar movies based on the text analysis.


