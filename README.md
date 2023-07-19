# Sentiment Classification on Reddit comments on Climate Change

## Project Abstract

This project takes the form of an investigative study in analyzing user comments posted on Reddit to determine the user’s sentiment on Climate Change. The study proposed to compare the classification capabilities of simple RNNs to learn semantics \& syntactic form of the comments versus other variants like LSTMs and GRUs that capture the long-term dependencies using word embeddings from pre-trained GloVe vectors. The importance of context is showcased clearly when we combine word embeddings from GloVe with a LSTM which results in a boost in the quality of results with a f1 score of 75\% vs 72\% f1 score for a simple RNN. We attempt to improve upon the performance of the simple LSTM by replacing it with a deep GRU architecture and use dropout and pre-trained word embeddings from GloVe to receive a f1 score of 77\%.

## Project files for the course 732A81

Link to the full dataset: https://www.kaggle.com/datasets/pavellexyr/the-reddit-climate-change-dataset?select=the-reddit-climate-change-dataset-comments.csv

Link to the cleaned dataset: https://www.kaggle.com/code/chekurinikhil/fork-of-climate-change-cleaned-comments-2/data
