# CineSense: Movie Recommendation System

CineSense is a movie recommendation application that uses cosine similarity to suggest movies based on user input. Built with Streamlit for the frontend, CineSense offers an intuitive interface for users to discover new films tailored to their preferences. The project is deployed on Streamlit Community Cloud and is accessible through the following link: [CineSense](https://cinesense.streamlit.app).

## Features

- **Movie Recommendations**: Get personalized movie suggestions based on your selected movie using cosine similarity.
- **Dynamic Sorting**: Sort recommendations by various criteria, including release year, rating, and popularity.
- **User-Friendly Interface**: Easily select a movie and the number of recommendations you desire.

## Usage

1. **Select a Movie**: Use the dropdown menu or type the movie name to select your desired film.
2. **Specify the Number of Recommendations**: Use the slider to choose how many movie recommendations you want.
3. **Choose Sorting Order**: Select how you would like to sort the recommendations.
4. **Get Recommendations**: Click the "Show Recommendation" button to display the suggested movies.

## Code Overview

The core functionality is defined in the `recommend` function, which processes user input and returns a list of recommended movies based on cosine similarity. The results can be sorted based on user preferences, including:

- Most Similar Content
- Newest First
- Oldest First
- Highest Rating
- Lowest Rating
- Most Popular
- Least Popular

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Acknowledgments

- Streamlit for the powerful framework that made this project possible.
- The dataset used for the movie information and similarity calculations.
