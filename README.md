# Movie Recommender System
This is a simple movie recommender system built using Python and Streamlit. The system recommends movies based on their similarity to the user's selected movie. The recommendations are generated using natural language processing techniques and cosine similarity.

## Getting Started
### Prerequisites
Before running the application, ensure you have the required dependencies installed. You can install them using the following command:

```bash
pip install -r requirements.txt
```
### Running the App
To run the app, use the following command:

```bash
streamlit run app.py
```
This will start the Streamlit development server, and you can access the app in your web browser at http://localhost:8501.

## Usage
1. Select a movie from the dropdown menu.
1. Click the "Show Recommendation" button.
1. The app will display the top 5 recommended movies along with their posters.
## Data Sources
The movie data used in this project comes from two datasets:

* `tmdb_5000_movies.csv`: Contains information about movies, such as title, overview, genres, keywords, etc.
* `tmdb_5000_credits.csv`: Contains information about movie credits, including cast and crew details.
## Model
The recommender system uses a combination of movie features, such as genres, keywords, cast, and crew. It employs natural language processing techniques to extract relevant information and calculate cosine similarity between movies.

## Files
* `app.py`: Main Streamlit application file.
* `model.py`: Contains the movie recommender system code.
* `requirements.txt`: Lists the required Python packages.
## Acknowledgments
* This project is inspired by the concept of collaborative filtering and content-based recommendation systems.
* The movie data is sourced from The Movie Database (TMDb).
Feel free to explore and enjoy the movie recommendations!
