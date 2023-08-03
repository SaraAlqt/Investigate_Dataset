# Project Name
Investigate a Dataset - [TMDb movie data]¶
## Description
In this project, I worked with a dataset containing information about movies from The Movie Database (TMDb). The dataset includes various attributes such as movie titles, genres, release dates, budgets, revenues, and user ratings.
I choose some research questions to explore using TMDb movie dataset and perform an investigation to find answers. I used Python and its libraries, such as NumPy, Pandas, and Matplotlib, to analyze and visualize the data.
Throughout the project,  I went through the data analysis process, including data wrangling, exploratory data analysis, drawing conclusions, and communicating my findings through a report.
## Dataset 
1-id-- rows unique id
2-imdb_id-- imdb unique id
3-popularity-- popularity score
4-budget-- budget of movie
5-revenue-- revenue of movie
6-original_title-- title of movie
7-cast-- cast in movie
8-homepage-- link of the movie website
9-director-- the name of the movie director
10-tagline-- tagline of movie
11-keywords-- keywords of movie
12-overview-- overview of movie
13-runtime-- the duration of movie
14-genres-- type of movie
15-production_companies-- name of the movie production company
16-release_date-- release data of movie
17-vote_count-- vote cast by viewers
18-vote_average-- average of votes cast by viewers
19-release_year-- release year of movie
20-budget_adj-- budget in 2010 dollars, accounting for inflation
21-revenue_adj-- revenue in 2010 dollars, accounting for inflation
## Research questions
Does a high-budget movie generate high revenue?
Does a high-budget movie have more popularity?
Which genre has produced the most films?
What are the top movies based on their average vote?
## Files
tmdb-movies.csv
## Results

![1](https://github.com/SaraAlqt/Investigate_Dataset/assets/141185254/7966b79f-86b8-4974-ae65-7c9ed8f0f8bb)

from the scatter plot, I can conclude that there is a positive correlation between budget and revenue


![2](https://github.com/SaraAlqt/Investigate_Dataset/assets/141185254/b0c72e42-ca3a-44a5-818f-e93159353f3a)
From the scatter plot, there is a positive correlation between budget and popularity.


![3](https://github.com/SaraAlqt/Investigate_Dataset/assets/141185254/2564ff70-6e28-43cd-851e-7f20e9211733)


From the pie chart, Drama has the highest number of movies by 17% the next is comedy by 13.2% and the last one is TV Movies.


![4](https://github.com/SaraAlqt/Investigate_Dataset/assets/141185254/829892f8-8fc0-4780-a132-405f7a1970a3)


The top 1 movie based on vote average is The Shawshank Redemption.


## Limitations
● The budget, revenue and runtime of some movies had equal to zero led me to delete a lot of rows.

● Duplicates in the data affect the result.
