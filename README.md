# Movie Recommender System with Streamlit

This is a movie recommendation system built using collaborative filtering techniques and deployed with Streamlit. The system provides personalized movie recommendations based on user preferences and ratings.

## Features

- Movie Selection: Users can choose a movie from the dropdown list or enter a movie name manually.
- Movie Recommendations: The system generates a list of recommended movies based on the selected movie.
- Movie Posters: The recommendations are displayed with movie titles and posters fetched from The Movie Database (TMDB) API.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/2202-Aryan/Movie_reccomender_system/
   
2. Install the required dependencies:
   pip install -r requirements.txt
3. Run the application:
   streamlit run mov_rec.py
   
## Project Structure

1. mov_rec.py: The main application file containing the Streamlit code for user interaction and recommendation display.
2. mov_list.pkl: Pickle file containing movie data in a dictionary format.
3. similarity.pkl: Pickle file containing similarity scores for movies based on collaborative filtering.
4. requirements.txt: Text file listing the required Python libraries and their versions.

## API Key
To fetch movie posters from TMDB, you need to obtain an API key. Follow these steps:

1. Sign up for an account on the TMDB website.
2. Generate an API key from your account dashboard.
4. Replace the API key in the fetch_poster function in mov_rec.py with your own API key.

url = "https://api.themoviedb.org/3/movie/{}?api_key=YOUR_API_KEY&language=en-US".format(movie_id)



   

