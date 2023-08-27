# Word2Vec Ophthalmology operative notes

## Features

A pre-trained Word2Vec model created using Gensim is based on ophthalmology operative notes. The model has a word-embedding dimensionality of 50.

## How to Load the Word2Vec Model

To load the custom-trained Word2Vec model, you can use the following Python code snippet:

```python
from gensim.models import Word2Vec

# Load the model
model = Word2Vec.load("word2vec_D50.model")
```
