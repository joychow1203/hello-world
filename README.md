# MA 705 Individual Project

## Dashboard Description

This dashboard allows users to find best mystery and horror movies from 182 top-rated movies in these genres based on the following search criteria: 
1) Select one or more year ranges to see details about movies released within the year range(s) in the table. While a movie can belong to more than one genre, the scatterplot presents the ratings and primary genres of the matched results on the timeline, 
2) Select a minimum rating to further search movies that have received a score above this number. The results are shown in the table.

### Data Cleaning
Data were compiled from RottenTomatoes and IMDB database. Two movie lists were scraped from RottenTomatoes, cleaned, and converted into a dataframe containing movie titles and released years. Duplicates were removed since several movies were included in both lists, resulting in 182 movies in total. On the other hand, # files from IMDB's database were merged according to each movie's unique ID to match movie specifics to viewer ratings. This information was then merged to the 182 interested movies according to each movie's original title and year. Title, original title, year, duration, genres, average IMDB rating, and number of votes were kept. Each movie's primary genre and year range were extracted based on available information.
Excel was also used in the data cleaning process to fix inconsistency. 

### Data Sources and References
- Top 100 Mystery & Suspense Movies: https://www.rottentomatoes.com/top/bestofrt/top_100_mystery__suspense_movies/
- Top 100 Horror Movies: https://www.rottentomatoes.com/top/bestofrt/top_100_horror_movies/
- Movie basics and ratings on IMDB: https://www.imdb.com/interfaces/
- https://dash.plotly.com/dash-core-components/dropdown
