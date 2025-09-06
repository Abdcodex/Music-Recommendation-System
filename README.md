# Music-Recommendation-System

Music Recommendation System: Utilizing K-means Algorithm for Enhanced Music
Discovery

The core of the system lies in the application of the K-means algorithm, a popular
unsupervised learning technique, to cluster songs based on their audio features.
The K-means algorithm is employed to partition these songs into distinct
clusters, with each cluster containing songs that share similar audio characteristics.

To generate personalized music recommendations, our system utilizes a two-step
process. In the first step, we identify the cluster to which a user's preferred songs
belong by comparing their audio features to the centroids of the song clusters. This
allows us to understand the user's musical preferences in terms of the identified
clusters. In the second step, we recommend songs from the clusters that align with
the user's preferences, thereby providing a tailored and personalized music selection.

