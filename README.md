# ETL
Simple ETL using SQLite and Python (Pandas)

This ETL project focused on extracting, transforming, and loading datasets about popular Coursera courses.

I first created two tables, courses, and rating. The courses table houses description of popular courses in Coursera. The rating table contains the rating for each course. The two tables are connected through a key.

I then loaded the data into the databases using the INSERT INTO clause for SQL.

On the second Python script, ETL.py, I used the Pandas library to extract the data from the two tables, transform the data for analysis, and then load the transformed data back to the database as another table. 
