# Movie-Recommender-System
A movie recommender system that implements different recommending techniques for a particular user.

POPULARITY BASED RECOMMENDER:
It works on the principle that movies that are more popular will have a higher probability of being liked by the average audience.This model does not give personalized recommendations based on the user.
But it suffers from various limitations.it gives the same recommendation to everyone, regardless of the user's personal taste. If a person who loves romantic movies (and hates action) were to look at our Top 10 Chart, he/she wouldn't probably like most of the movies.


CONTENT BASED RECOMMENDER:
To personalise the recommendations more, we build an engine that computes similarity between movies based on certain metrics and suggests movies that are most similar to a particular movie that a user liked. Since we will be using movie metadata (or content) to build this engine, this also known as Content Based Filtering.

COLLABORATIVE FILTERING BASED RECOMMENDER:
The recommendations are done based on the user’s behavior. History of the user plays an important role. For example, if the user ‘A’ likes ‘Coldplay’, ‘The Linkin Park’ and ‘Britney Spears’ while the user ‘B’ likes ‘Coldplay’, ‘The Linkin Park’ and ‘Taylor Swift’ then they have similar interests. So, there is a huge probability that the user ‘A’ would like ‘Taylor Swift’ and the user ‘B’ would like ‘Britney Spears’. This is the way collaborative filtering is done.
