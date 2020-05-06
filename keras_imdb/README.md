# Sentiment Analysis of imdb movie reviews using Deep Learning (RNN LSTM)

The dataset is keras build in imdb movie review.

 ### **1. Information about the dataset**
IMDB Movie reviews sentiment classification
Dataset of 25,000 movies reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a sequence of word indexes (integers). For convenience, words are indexed by overall frequency in the dataset, so that for instance the integer "3" encodes the 3rd most frequent word in the data. This allows for quick filtering operations such as: "only consider the top 10,000 most common words, but eliminate the top 20 most common words".

As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.


 ### **2. Model**
 
 
 
 Layer 1 - Embedding - Converts word tokens i.e integers into dense vectors called embedding.These gets updated while traning the module.
 Layer 2 - LSTM - 
 Layer 3 - Dense - 1 neuron output - activation as sigmoid - 

![alt text](keras_imdb/sentiment_analysis_rnn.JPG)
