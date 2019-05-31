# thaipoetrygenerator

An experimental Thai poetry generator using RNN language models:

This is my final project for "Introduction to Computational Linguistics" at Chulalongkorn University.

I use keras to train RNN model to predict characters given fixed length input sequences. 
There are 2 models used(18/05/19) (loadable with keras.models.load_model):
1. 1-layer LSTM stacked on a Dense layer (can be found on repo file)
2. Embedding Layer stacked on 3-Layer LSTMs with dropout (can be downloaded here https://drive.google.com/file/d/1KyJAozfjJFC_cqSByR1RH_wfnurfrmIW/view)

The training/generation/evaluation procedures can be found at
https://colab.research.google.com/drive/18RNQODEK5fmqIerBaNbJRPecEJeZbSkC#scrollTo=C9yPptFc3CHy&uniqifier=1

The code (ipynb file) and data is available in the repo files.
Moreover, there is a report of the experiment, as well as detailed explanations in report.pdf, 
also available in the repo file (written in Thai).
