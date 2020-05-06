# Sentiment Analysis of imdb movie reviews using Deep Learning (RNN LSTM)

The dataset is keras build in imdb movie review.

 ### **1. Information about the dataset**
IMDB Movie reviews sentiment classification
Dataset of 25,000 movies reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a sequence of word indexes (integers). For convenience, words are indexed by overall frequency in the dataset, so that for instance the integer "3" encodes the 3rd most frequent word in the data. This allows for quick filtering operations such as: "only consider the top 10,000 most common words, but eliminate the top 20 most common words".

As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.


 ### **2. Model**
 

 
 
 Layer 1 - Embedding - Converts word tokens i.e integers into dense vectors called embedding.These gets updated while the module is      learning

Layer 2 - LSTM -   Embeddings of words are fed to this layer.This layer studies the sequence of data and produces a encoded sequence.LSTM has ability to remenber previous information and hence can be used for this appication.
 
 Layer 3 - Dense - 1 neuron output - activation as sigmoid - input is the output from the last timestep of LSTM layer. Gives positive or negative sentiment.



### **3. Result**
With training on 16000 samples and with 4 epochs-
Training Accuracy obtained - 92%
Testing on 8000 samples Accuracy - 85%
