# recommender-systems

In this project, we make an anime recommender system for the given dataset.

The download link of the dataset:

https://drive.google.com/file/d/1qgvmZEOJiyb2Lkh3VSPwjA6xVbFyZhWT/view

This dataset includes anime and rating files. The anime file contains the information of a large number of animes and the rating file contains the scores that users have given to different animes.

Section 1: Collaborative Filtering

In this section, we implement the item-based collaborative filtering method on the scores given by users to different animes. Now we can recommend new animes to users based on scores.

![1_3ALliiz9hG79_2xopzgyrQ 2 57 20 AM](https://user-images.githubusercontent.com/47056654/195467508-cf80c6ca-fae4-49a3-8144-c67da48b32b0.jpg)

Section 2: Content-Based Recommendation 

In this section, we perform the content-based recommendation on the animes that a user has watched. Now we can recommend new animes to the user according to the information available from different animes.

![recommendation-system11](https://user-images.githubusercontent.com/47056654/195469234-5b738a5f-c9eb-4429-9ac8-9f7dea6362a6.jpg)

Section 3 

In the last part, we try to get a better result than the previous two methods by using a combination of content-based recommendation and collaborative filtering methods. We start with the content-based recommendation and obtain ID of animes that are related to the user's interest. Now we have the ID of animes that are related to the user's interest. In the next step, we limit the rating dataset with these IDs then we apply the content-based collaborative filtering to the limited dataset.

