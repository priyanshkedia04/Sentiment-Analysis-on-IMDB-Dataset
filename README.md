# Sentiment-Analysis-on-IMDB-Dataset
Performed Sentiment Classification on IMDB Review dataset. The reviews were classified as Positive (1) and Negative (0) using Recurrent Neural Networks. Both the training and testing set had 37,500 examples each making a dataset total of 75,000 Reviews. Word Embeddings were trained with 10,000 most occurring words having 64 dimensions. The model consisted of a GRU layer followed by a Dense Layer. The model was made in Keras using Tensorflow at the backend. NLTK was used for cleaning, Stemming, and Lemmatization of the text, and removal of stop words was also done.

Training Accuracy: 99.08%

Validation Accuracy: 94.83%

Test Accuracy: 93.13%
