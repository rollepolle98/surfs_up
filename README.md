# Surf's Up with Advanced Data Storage and Retrieval 

## Background and Purpose

The purpose of this challenge is to give W. Avy further analysis due to the fact that he will be opening a surf and ice cream shop and would like to know more about temperature trends prior to opening. Specifically he wants the temperature data for the months of June and December in Oahu. So we started off by pulling data from an SQLite data base and created summary statistics comparing the month of June to the month of December. The purpose behind these summary statistics is to determine whether or not the surf and ice cream shop will be sustainable year around. These statistics will help provid Mr.AVy with accurate information that will allow him to make important business decisions therefore I must be accurate when analyzing and calculating this information.



## Analysis and Results

Using Python, Pandas functions and methods, and SQLAlchemy, I had to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. From there I then converted those temperatures to a list, created two DataFrame's from each list, and generated the summary statistics for each month. This process was done by creating a query that filters the date column from the measurment table to obtain all the temperatures for the months of June and December.

Below you can see the summary statistics for the month of June.


Below you can see the summary statistics for the month of December.


## Summary and Conclusion
