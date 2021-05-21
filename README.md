# Extract, Transfrom, Load Movie Data

## Overview

The purpose of this project was to gather movie data from both wikipedia and kaggle and create a database that students can use to preform there own analysis. In order to do these, I extracted the neccessary data from Wikipedia and Kaggle, used python's pandas library to transform the data into a working dataframe, and then loaded it to PostgreSQL for students to use it.

## Results

After completing the extract, transform, and load process, I had a database with two tables: one for movies and one for ratings. The movies table consists of 31 columns holding a range of information for 6048 different movies.
![Movies_Query](https://github.com/mahmoodsayedi/ETL/blob/main/resources/movies_query.png) 
The ratings table consists of 5 different columns holding a range of information on over 26 million individual user ratings.

![Rating_Query](https://github.com/mahmoodsayedi/ETL/blob/main/resources/ratings_query.png) 
Together, students will have a chance to preform various different analysis from these tables to derive all sorts of interesting insights.

