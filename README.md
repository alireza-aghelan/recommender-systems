# recommender-systems

In this project, we made a recommender system for the given dataset.

The download link of the dataset:

https://drive.google.com/file/d/1qgvmZEOJiyb2Lkh3VSPwjA6xVbFyZhWT/view

This dataset contains information of a large number of animations and the points given by different users to these animations.

Note: in order to use the data in the dataset, various pre-processing is required

Section 1: Collaborative Filtering

At first, we implemented the collaborative filtering method on the scores given by users to different animations, and based on them, we proposed different animations to the user.
In this section we used item-based collaborative filtering

![1_3ALliiz9hG79_2xopzgyrQ 2 57 20 AM](https://user-images.githubusercontent.com/47056654/195467508-cf80c6ca-fae4-49a3-8144-c67da48b32b0.jpg)

Section 2: Content-Based Recommendation 

In this section, we performed the content-based recommendation on the animations that a user has watched, and we recommended a new animation to each user according to the information available from different animations.

![recommendation-system11](https://user-images.githubusercontent.com/47056654/195469234-5b738a5f-c9eb-4429-9ac8-9f7dea6362a6.jpg)

Section 3 

In the last part, we tried to get a better result than the previous two methods by using a combination of content-based recommendation and collaborative filtering methods. We started with the content-based recommendation and obtained code movies that are related to the user's interest. Now we have the code of the movies that are related to the user's interest. In the next step, we limit the rating dataset with these codes then we apply collaborative filtering to the limited dataset.

