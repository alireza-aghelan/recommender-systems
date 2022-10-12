# recommender-systems

In this project, we made a recommender system for the given dataset.

you can download the dataset related to the project from this link.
https://drive.google.com/file/d/1qgvmZEOJiyb2Lkh3VSPwjA6xVbFyZhWT/view

This dataset contains information of a number of animations and points given by different users to these animations in the form of two CSV files.

Section 1: Collaborative Filtering

at first, we implemented the collaborative filtering method on the scores given by users to different animations, and based on them, we proposed different animations to the user.

![1_3ALliiz9hG79_2xopzgyrQ 2 57 20 AM](https://user-images.githubusercontent.com/47056654/195467508-cf80c6ca-fae4-49a3-8144-c67da48b32b0.jpg)

Section 2: Content-Based Recommendation 

in the next step, we performed information filtering or Content-based recommendation on the animations that a user has watched, and we recommended a new animation to each user according to the information available from different animations.

Section 3: in the last part, we tried to get a better result than the previous two methods by using another method. 

in this part, we can use the combination of previous concepts, creative methods resulting from the combination of previous methods, machine learning, etc.

we used the combination of content-Based recommendation and collaborative filtering methods.
we started with Content-Based Recommendation and obtained code movies that are related to the user's interest.
now we have the code of the movies that are related to the user's interest. 
in the next step we limit rating dataset with these codes then we apply collaborative filtering on new dataset.

Note: in order to use the data in the dataset, various pre-processing is required


