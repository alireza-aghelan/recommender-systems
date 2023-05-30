# Recommender system

In this project, we make an anime recommender system for the given dataset.

The download link of the dataset:

https://drive.google.com/u/0/uc?id=1mipJf49ZvqD3CArtutXNOJriqdtb9tAH&export=download

This dataset includes anime and rating files. The anime file contains the information of a large number of animes and the rating file contains the scores that users have given to different animes.

# Section 1: Collaborative Filtering

In this section, we implement the item-based collaborative filtering method on the scores given by users to different animes. Now we can recommend new animes to users based on scores. Note: In cases where the user has not rated any animes, this method cannot recommend an anime.

# Section 2: Content-Based Recommendation 

In this section, we perform the content-based recommendation method on the animes that a user has watched. Now we can recommend new animes to the user according to the information available from different animes.

# Section 3 

In the last section, we try to get a better result than the previous two methods by using a combination of content-based recommendation and collaborative filtering methods. We start with the content-based recommendation method and obtain the IDs of animes that are related to the user's interest. In the next step, in the rating dataset, we keep the records that contain these IDs and delete the rest. Finally, we implement the collaborative filtering method on the smaller rating dataset. In cases where the user has not rated any animes, only the content-based method has been used to recommend the animes.
