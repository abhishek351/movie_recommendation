# movie_recommendation

Content-based recommender using Natural Language Processing (NLP). A guide to build a content-based movie recommender model based on NLP

In this article, I have combined movie attributes such as 'genres','keywords','tagline','director','cast' to calculate its cosine similarity with another movie. The dataset is has 5000 movie dataset.

The data has to be pre-processed using NLP to obtain only one column that contains all the attributes (in words) of each movie. After that, this information is converted into numbers by vectorization, where scores are assigned to each word. Subsequently cosine similarities can be calculated.
