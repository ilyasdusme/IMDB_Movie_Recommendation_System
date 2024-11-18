# IMDB Movie Recommendation Analysis

This project analyzes user ratings for movies to identify correlations and recommend similar movies. The dataset includes user ratings and movie titles, providing a simple recommendation system.

# Features

- **Data Loading and Preprocessing:**  
  - User ratings are loaded from the `users.data` file.  
  - Movie titles are added using the `movie_id_titles.csv` file.  

- **Data Analysis:**  
  - A pivot table is created for user-movie ratings.  
  - Correlation analysis is performed for movie recommendations (e.g., movies similar to "Star Wars (1977)").  
  - Average ratings and total vote counts are calculated.  

- *Filtering:* 
  - Recommendations are filtered to include only movies with at least 100 ratings.

## Requirements

This project requires the following Python libraries:

- `numpy`  
- `pandas`  

You can install these libraries using pip:

```bash
pip install numpy pandas
```

# How to Run

1. Clone this repository.  
2. Ensure the following data files are present in the project directory:  
   - `users.data`  
   - `movie_id_titles.csv`  
3. Open the Jupyter Notebook (`imbd.ipynb`) and execute the cells in order.

