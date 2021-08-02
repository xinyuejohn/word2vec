# word2vec

The goal is to obtain the vector representations for words from text. We'll be working with a subset of reviews for restaurants in Las Vegas.

The main idea is that words appearing in similar contexts have similar meanings. Because of that, word vectors of similar words should be close together. Models that use word vectors can utilize these properties, e.g., in sentiment analysis a model will learn that "good" and "great" are positive words, but will also generalize to other words that it has not seen (e.g. "amazing") because they should be close together in the vector space.

The word2vec project includes:
- Load data
- Create word pairs
- Model definition
- Training
- Analogies
