# Recommendation-System

**Data Loading and Preprocessing** - We start by loading the movie ratings data from a file. This dataset contains information about which customer gave what rating to which movie. We then assign unique identifiers to movies and perform some initial calculations like summarizing ratings by movie and customer.

**Data Trimming** - To make accurate recommendations, we remove movies with too many ratings (which could be biased by popularity) and customers who have given too few ratings (which might not provide reliable information).

**Creating a User-Movie Matrix** - We transform the data into a user-movie matrix, where each row corresponds to a user, each column corresponds to a movie, and the values in the matrix are the ratings. This matrix helps us understand how users relate to movies.

**Generating Recommendations for a User** -
We choose a specific user to generate personalized recommendations.
Based on the trained SVD model, we estimate how the user might rate movies they haven't seen.
We then sort these estimated ratings to provide a list of recommended movies.
