# Movie-Recommendation-Project

This project is a **Movie Recommendation System** that suggests movies based on their similarity to a user's favorite movie. The recommendation engine is built using **cosine similarity** to identify movies that share similar features like genres, keywords, and cast.

## Project Overview

The goal of this project is to enhance user experience by recommending movies similar to those they already enjoy. It processes the dataset to extract relevant features and calculates the similarity between movies to provide meaningful suggestions.

### Dataset

- The dataset used consists of 4803 movies with 24 attributes including:
  - **Title**: The name of the movie.
  - **Genres**: The categories or genres the movie belongs to.
  - **Keywords**: Keywords associated with the movie's plot or themes.
  - **Overview**: A brief summary of the movie.
  - **Cast and Crew**: Information about the actors, directors, and other key personnel involved.
  - **Popularity, Vote Average, and Vote Count**: Metrics related to audience feedback and ratings.

## Features

- **Cosine Similarity**: The recommendation engine uses cosine similarity to compare movie features and suggest similar titles based on user input.
- **Text Vectorization**: The textual data (like movie overviews and keywords) is processed and converted into vectors to calculate similarities between movies.
- **Content-Based Recommendations**: The system is content-driven, focusing on movie attributes such as genres, keywords, and the cast to make recommendations.

## Installation

To run the project locally:
1. Clone the repository and navigate to the project directory.
2. Install the necessary dependencies from the `requirements.txt` file.
3. Run the Jupyter Notebook to explore and use the recommendation engine.

## Usage

The system allows users to input a movie title and receive a list of similar movies. The results are based on various attributes like genres, keywords, and the movie's cast.

### Example:
- Input: `The Dark Knight`
- Output: A list of movies that are thematically or stylistically similar to **The Dark Knight**.

## Features Overview

- **Similarity Score**: For each recommended movie, a similarity score is calculated based on the cosine similarity metric.
- **Content Matching**: Movies are matched based on shared genres, keywords, and personnel, offering recommendations that align with user preferences.

## Contributing

Contributions are welcome! If you would like to improve the system or add additional features, feel free to submit a pull request or open an issue for discussion.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Cosine Similarity** for powering the recommendation system.
- Dataset sourced from **Kaggle**.
- Special thanks to the open-source community for inspiration and resources.

## Owner

- **Project Owner :-** Shubham Parihar
- **Link Of Linkedin :-** https://www.linkedin.com/in/shubhamparihar7/
