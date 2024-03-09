# Word Embeddings with Continuous Bag-of-Words (CBOW), Skip-gram, and Word2Vec

This repository provides implementations and examples of word embeddings using various techniques including Bag-of-Words (BoW), Continuous Bag-of-Words (CBOW), Skip-gram, and Word2Vec. Word embeddings are dense vector representations of words, capturing semantic meanings and relationships between words in a corpus.

## Techniques

### Continuous Bag-of-Words (CBOW)

CBOW aims to predict the target word based on its surrounding context words. It takes a fixed-size context window and predicts the target word within this window. CBOW is trained by maximizing the probability of predicting the target word given its context.

### Skip-gram

Skip-gram is the inverse of CBOW. It aims to predict context words based on the target word. Given a target word, skip-gram predicts the context words within a fixed-size window around the target word. Skip-gram is trained by maximizing the probability of predicting context words given the target word.

### Word2Vec

Word2Vec is a popular word embedding technique developed by Google. It includes both CBOW and Skip-gram models. Word2Vec learns vector representations of words by training a neural network to predict context words given target words (Skip-gram) or vice versa (CBOW).

## Contents

- `cbow_embeddings.py`: Implementation of Continuous Bag-of-Words (CBOW) word embeddings.
- `skipgram_embeddings.py`: Implementation of Skip-gram word embeddings.
- `word2vec.py`: Implementation of Word2Vec embeddings combining CBOW and Skip-gram approaches.

