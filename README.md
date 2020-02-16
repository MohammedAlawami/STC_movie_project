# STC_movie_project

The IPTV dataset contains the following features with more than 5 million rows and the size of
data is more than 1 Gigabytes.

* User ID
* SESSION START (DATE/TIME)
* SESSION DURATION
* PROGRAM NAME
* PROGRAM DESCRIPTION
* PREOGRAM GENRE
* PROGRAM CLASS
* SERIES TITLE
* SERIES NAME
* Episode title
* Episode number

## The Challenges 
1. Technical (algorithm) challenges ( 80% of total score )
    * Build machine-learning model to predict the top 10 items (movie, series) which the user will watch in future (60 %)
        * The final model should take as input a list of (user IDs) and output the result for each user
        * The list of items (movie, series) to choose from (rank) will be given
        * The user that we will test on, will have historical data in the training set
    * Determine user profiling (20 %)
        * How many real users for the same account and their gender and age
2. Presentation challenges ( 20% of total score )
    * Determine the best way to present the result (i.e. long tail plot for a given user)

