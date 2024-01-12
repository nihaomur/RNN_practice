# RNN Practice
This repository encompasses multiple files utilized for practicing the construction of RNN-based models.

## [SimpleRNN](SimpleRNN.ipynb)
In this file, I utilized the *simpleRNN model* to predict the next letter based on several preceding letters from the English alphabet as input.

## [LSTM with Embedding](LSTM_with_Embedding.ipynb)
Similar to the task in SimpleRNN, I used an *Embedding layer* to perform *word2vec* on the alphabet and utilized *LSTM* to predict the subsequent letters. In comparison to SimpleRNN, an accuracy of 100% was achieved in a very short number of epochs.

## [Embedding_RNN](Embedding_RNN.ipynb)
Using the built-in IMDb sentiment analysis database provided by Keras, I incorporated an embedding layer before training. Following this, I employed LSTM/GRU layers for model training. The accuracy achieved was close to 90%, demonstrating a promising performance.
