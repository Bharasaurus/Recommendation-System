# Netflix-Recommendation-System

Data Text File contains the rating of a certain movie ID that is rated by several people with respective ID and on a Specific Date
Movie Name CSV File contains the movie ID, Movie Name and the Date

Rating --> Float
Customer ID --> Int
Movie ID --> Int

Adding another Movie ID Column into the Netflix Dataset.
After that EDA is performed where the less rated and number of rating per movie is huge in number are removed form the dataset.
Two Filters Applied --> Less Rated Movies and Remove Customers who rate very less (May be considered as spam)
SVD - Singular Value Decompostion --> This helps compress a huge dataset and also not loose much data in process

Recommendation Process -
1. What Movies/Series you have watched before
2. What Similar movies you watched and rated 5, is compared to another random person who watched that same movie and rated it 5. So the movies he rated 5 will also be recommeneded to you
