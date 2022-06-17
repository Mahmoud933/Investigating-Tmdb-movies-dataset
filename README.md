# Investigating-Tmdb-movies-dataset
Udacity Data Analyst Term 1 Project: Investigate a Dataset (TMDb movie data)
In this project, I analyzez a dataset and communicated my findings about it. I used the Python libraries NumPy, Pandas, and Matplotlib to do the analysis

This Python script is written for Project 3 (Term 1) of Udacity's Data Analyst Nanodegree (DAND) and is used to explore TMDb movie data. But what determines if a movie is considered as good or bad? There could be several factors influencig the quality of a movie, as for example the budget, genre, etc. This little project helped the author to improve his data analytics skills and explore some of the success criteria for movies.

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis.

How to run the script
You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. The code was written in Jupyter Notebook.

Datasets
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

Variables:

id

imdb_id

popularity

budget

revenue

original_title

cast

homepage

director

tagline

keywords

overview

runtime

genres

production_companies

release_date

vote_count

vote_average

release_year

budget_adj

revenue_adj

Files

tmdb-movies.csv

Questions to answer

Question 1:How long is the average movie runtime?

Question 2:Which year has the highest release of movies?

Question 3:Which length movies most liked by the audiences according to their popularity?

Question 4:What is the Average Runtime Of Movies From Year To Year?

Question 5:Is the rating of movies getting better or worse or staying the same over time?

Question 6:What is the highest rated movie?

Question 7:What is the most popular genre over the years?

Conclusions
1-Highest rated movie is 'Jurassic World'

2-Movie ratings are getting worse overtime

3-Highest average rating year is 1973 while 2012 had the lowest average rating for movies

4-Runtime decreased signficantly over the years

5-Average runtime of movies is 109 mins

6-Highest movie runtime year is 1965 while the lowest is 1987

7-Highest movie average vote year is 1960 while the lowest is 2000

8-2011 had the highest number of movies produced while 1969 had the lowest

9-There is a strong positive correlation between profit and revenue

10-As the budget for the movie increases the revenue increases

11-Drama is the most popular genre of movies

limitations: 1-budget and revenue had alot of zeroes also they do not have a currency

2-incorrect datatypes

3-i had to drop a lot of NA values
