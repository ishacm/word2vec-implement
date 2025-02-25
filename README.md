## Word2Vec & GloVe Embeddings on Reddit Dataset

A minimal and efficient implementation of Word2Vec and GloVe embeddings using a Reddit dataset. This project highlights key NLP techniques while keeping compute requirements low.

### Features

Pretrained GloVe Embeddings (50D from Wikipedia)

Custom Word2Vec Training on a 10% sample of the Reddit dataset

Skip-gram Model implementation

Comparison of Word Similarity between Word2Vec & GloVe

UMAP-based Visualization of learned word embeddings

### Dependencies

gensim

nltk

datasets

matplotlib

umap-learn

### Installation

pip install gensim nltk datasets matplotlib umap-learn

### Usage

Run the script to:

Load GloVe embeddings

Process Reddit dataset (10% sample)

Train a Word2Vec model (Skip-gram)

Find similar words using both models

Visualize embeddings

### Results

Word2Vec vs. GloVe Similarity Comparison

t-SNE / UMAP-based Word Embedding Visualization

### License

MIT License.
