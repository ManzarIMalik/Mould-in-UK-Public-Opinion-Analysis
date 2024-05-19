# Mould in UK - Opinion Mining & Analysis

This repository contains code for performing topic modeling on Reddit data using Python.

## Notebook Overview

The notebook includes the following steps:

### Importing Libraries and Modules

Libraries such as `gensim`, `nltk`, `praw`, `spacy`, and `BERTopic` are used for text processing and topic modeling.

### Extracting Data from Reddit

The script uses the `praw` library to extract data from Reddit. **Note:** This step may take up to 10 minutes depending on the volume of data.

### Preprocessing Data

Text preprocessing steps such as tokenization, stopword removal, stemming, and lemmatization are performed using `nltk` and `spacy`.

### Building Topic Models

Various topic modeling techniques including LDA (Latent Dirichlet Allocation), NMF, and BERTopic are used to analyze the data.

### Visualizing Topics

Visualization tools such as `pyLDAvis` are used to interpret the topic models.
