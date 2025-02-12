IMDB Movie Genre Analysis
This Python project analyzes trends in movie data from IMDB, spanning the years 1966 to 2015. The analysis focuses on identifying key patterns across genres in terms of budget, revenue, popularity, and voting averages.

Research Questions
The project aims to answer the following questions:

1) Which genres are the most common?
2) Which genres have the highest average budget and revenue?
3) Which genres have the highest average popularity?
4) Which genres have the highest number of movies with a voting average ≥ 8?

Features:
Data Cleaning: Removed duplicates and reformatted multi-genre entries for accurate analysis.
Data Visualization:Used Seaborn to create charts and visualizations for genre-based trends.
Technologies Used Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib
Jupyter Notebook for code execution and iterative analysis

How to Run the Project:
Clone or download this repository.
Ensure you have Python installed (version 3.8 or higher is recommended).
Make sure to change the location in
movies = pd.read_csv(r'C:\Users\emili\Downloads\imdb_movies.csv')
as your computer will almost surely not have it stored in the same place.
Run the cells in the notebook sequentially to replicate the analysis.

Results and Insights:
This project provides answers to the research questions with supporting visualizations, including:
Future Improvements
Expand the analysis to include trends over time (e.g., how genres' popularity evolves).
Create more visualizations using Seaborn
Incorporate additional features like director or actor data for deeper insights.
