# Project-2
Metis Project 2: Predicting Rock Climbing Route Popularity

## Description
Build a regression model to predict the popularity of rock climbing routes.

## Features and Target Variables
Features collected: Rating, votes, height, pitches, photos, comments, difficulty (grade), safety, commitment, aid grade, number of nearby routes, sport/trad difficulty, grade difference nearby routes, and type of climb.

Features used in final model: Height, difficulty, and type of climb.

Target: Popularity, which was calculated by using a bayesian estimation on rating and votes.

## Data Used
Over 5,000 rows of data were scraped from [Mountain Project](https://www.mountainproject.com/).

## Tools Used
* BeatifulSoup
* Pandas and numpy
* Seaborn
* Matplotlib
* Sklearn

## Techniques Used
* Linear Regression
* Feature Engineering and Selection
* Web scraping
* LASSO

## Possible Impacts
The results from this model showed that as height and difficulty increase, the popularity of the route increases. Additionally, it looks as though aid and alpine climbs are more popular, while boulders are less popular. This information could potentially be used by people creating routes, so that if their goal is to create regularly climbed and highly rated routes, they would have some information regarding features that might allow them to identify popular routes.
