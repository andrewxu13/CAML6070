
# Movie Recommender Engine Using kNN

## Overview

This project aims to build the core of a movie recommender system, similar to those used by platforms like Amazon, Medium, Netflix, and YouTube. Given a dataset of movies, the recommender system identifies the 5 most similar movies to a movie query based on genre information and IMDb ratings.

## Data Source

The dataset used in this project is a subset of data extracted from the UCI's IMDb dataset, containing thirty movies across seven genres with their IMDb ratings. The dataset is available at:

```
https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv
```

## Implementation

The recommender system is implemented using Python and the scikit-learn library. The k-Nearest Neighbors (kNN) algorithm is utilized to find movies similar to a given query movie based on the genres and IMDb ratings.

### Example Query

An example use case of the recommender system is to find movies similar to "The Post", with the following genre and rating details:

- IMDb Rating: 7.2
- Biography: Yes
- Drama: Yes
- Thriller: No
- Comedy: No
- Crime: No
- Mystery: No
- History: Yes

The system will return the top 5 similar movies based on this query.

## Requirements

- Python 3.x
- Scikit-learn
- Pandas
- NumPy

## Setup and Execution

1. Clone the repository to your local machine.
2. Ensure that Python 3.x and all required libraries are installed.
3. Run the Jupyter notebook `CA05_V2.ipynb` to see the implementation and results.
