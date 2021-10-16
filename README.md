# Movies-ETL

## Analysis Overview
We are helping Amazing Prime (AP) to setup a database as they are going to hold a Hackathon where programmers work together over a short period of time on a project.  We are working with Britta from AP to gather and clean data from Wikipedia and Kaggle, put them together and load to the SQL database.  We are helping with the ETL process - Extract data from sources, Transform data and the Load to a database for storaage and analysis (in this case we are using SQL).  

## Results

- After Extracting, Transforming and Loading the Kaggle and Wikipedia data, we have a fairly robust file for teams in the Hackathon to more efficiently be able to analyze data to help Amazing Prime with their project.  The table we ended up with has 6,075 movies to analyze.
 
![Table query of count of movies](https://github.com/tessiertodd/Movies-ETL/blob/main/movies_query.png)

- We also retrieved, transformed and loaded another table which contains ratings about movies to further help teams with analysis... 26,024,289!!

![Table of query of count of ratings](https://github.com/tessiertodd/Movies-ETL/blob/main/ratings_query.png)


## Summary

While using refactored code to accomplish this task, it still required a fair bit of work to complete... but feels good to have accomplished that.  Here is a view of how much time it took (in seconds) when uploading all the different chunks of rattings table (good idea to chunk out when bringing in so much data in case something goes wrong partway through... at least we wouldn't lose all the data we uploaded to the point in the SQL table).

![Table for time to upload ratings data to sql table](https://github.com/tessiertodd/Movies-ETL/blob/main/ratings_import_time.png)
