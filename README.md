# thaipoetrygenerator

An experimental Thai poetry generator using RNN language models:

This is my final project for "Introduction to Computational Linguistics" at Chulalongkorn University.

I use keras to train RNN model to predict characters given fixed length input sequences. 
There are 2 models used(18/05/19):
1. 1-layer LSTM stacked on a Dense layer
2. Embedding Layer stacked on 3-Layer LSTMs with dropout

The training/generation/evaluation procedures can be found at
https://colab.research.google.com/drive/18RNQODEK5fmqIerBaNbJRPecEJeZbSkC#scrollTo=C9yPptFc3CHy&uniqifier=1

The code (ipynb file), data, and trained model is available in the repo files.
Also, there is a report of the experiment, as well as detailed explanationss in report.pdf (written in Thai).
