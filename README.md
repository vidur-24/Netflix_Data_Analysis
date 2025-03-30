# Netflix Data Analysis Project

## Overview

This project analyzes Netflix movie data using Python's data science libraries. It involves data cleaning, preprocessing, and visualization to extract insights from the dataset. The analysis answers several key questions about Netflix movies, such as the most frequent genre, the highest-rated movie, and the most popular movie.

## Dataset

The dataset contains the following attributes:

- **Release Date**: Year the movie was released
- **Title**: Name of the movie
- **Overview**: Short description of the movie
- **Popularity**: Popularity score
- **Vote Count**: Number of votes received
- **Vote Average**: Average rating of the movie
- **Language**: Language of the movie
- **Genre**: Category of the movie
- **Poster-Url**: Link to the movie poster

## Objectives

The analysis focuses on answering the following questions:

1. What is the most frequent genre of movies released on Netflix?
2. Which movie has the highest rating (vote average)?
3. What movie has the highest popularity? What is its genre?
4. What movie has the lowest popularity? What is its genre?
5. Which year had the most movies released?

## Tools & Technologies Used

- **Language** : Python
- **Libraries** : NumPy, Pandas, Matplotlib, Seaborn
- **Tools** : Jupyter Notebook

## Data Cleaning & Preprocessing

- Ensured the dataset has no missing (NaN) or duplicate values.
- Converted the `Release_Date` column to datetime format and extracted only the year.
- Dropped unnecessary columns: `Overview`, `Original_Language`, and `Poster-Url`.
- Identified and handled noticeable outliers in the `Popularity` column.
- Categorized the `Vote_Average` column for better analysis.
- Cleaned and categorized the `Genre` column by handling comma-separated values and white spaces.

## Visualizations & Insights

- **Bar chart** for the most frequent genre of movies.
- **Histogram** for the highest-rated movie (vote average distribution).
- **Bar chart** for the number of movies released per year.

## How to Run the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/vidur-24/Netflix_Data_Analysis.git
   ```
2. Navigate to the project folder:
   ```sh
   cd netflix-data-analysis
   ```
3. Install dependencies:
   ```sh
   pip install numpy pandas matplotlib seaborn
   ```
4. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
5. Open and execute the analysis notebook.

## Conclusion

This project provides insights into Netflix's movie trends and patterns using data analysis techniques. It helps in understanding popular genres, high-rated movies, and yearly movie trends on the platform.

## Future Improvements

- Expand the dataset with TV shows and series.
- Perform sentiment analysis on movie reviews.
- Develop a movie recommendation system using machine learning.