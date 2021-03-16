# ETL
Simple ETL using SQLite and Python (Pandas)

This ETL project focused on extracting, transforming, and loading datasets about popular Coursera courses.

In the first Python script Create_Tables.py, I used the CREATE TABLE clause to create two tables, courses, and ratings. The courses table houses descriptions of popular courses in Coursera. The ratings table contains the rating for each course. The two tables are connected through a key (courses.id and ratings.course_id).

I then loaded the data into the tables using the INSERT INTO clause of SQL.

On the second Python script, ETL.py, I used the Pandas library to extract the data from the two tables, transform the data for analysis, and then load the transformed data back to the database as another table. 
