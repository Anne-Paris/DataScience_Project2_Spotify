# DataScience_Project2_Spotify
# Project2: Spotify Dataset: What makes a song popular?
MATH-3439-01 Project 2

## Introduction
Popular songs don’t just pop out of nowhere, there are factors that cause songs to be popular. Using Spotify’s dataset, the main objective of our project was to get an understanding of which of these factors make a song popular, and use those to create a linear regression model to predict the popularity of any song.

## A little bit about our data...

Our data didn’t have any missing values, had 170k songs/rows and included songs released anywhere between 1921 and 2021. Most columns in our dataset were descriptive statistics for continuous variables. For our analysis, we discarded columns due to inconsistency/redundancy as well as those showing no trends. The discarded columns were: Artist name, release date (which was inconsistent as a date time, sometimes having months/days or just years), tempo, speechiness, mode and key.  

## Summary:
After looking at all variables and analyzing the ones that seemed to influence popularity, we came up with a model that was able to predict values up to 80, had a R^2 of 0.84 but a high MSE of 146 (it was still struggling to predict very popular songs (popularity of 70+). 
