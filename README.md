# Movies ETL

## Project Overview 

The purpose of this project was to gather Movie data from multiple sources, transform it, and load it into a database to be later analyzed by the streaming service Amazing Prime Video. They want to be able to anticipate which low-budget movies will become successful so that they can buy the movie rights to include them in their streaming service platform.

For this project, I worked with a Wikipedia JSON file and a Kaggle CSV file. I used Pandas DataFrames to merge the files, drop columns, remove null values, change column names, and fill in missing data. Within the DataFrames, I created functions, using for-loops, list comprehensions and regular expressions to clean the data. I finally created a function to export the data into an SQL database.  
