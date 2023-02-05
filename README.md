# NLP-Basics
This .ipynb file contains the implementation of some of the basic NLP concepts such as Tokenization, Text cleaning, Stopwords, Stemming, Lemmatization and feature extraction technique including Bag of words. below is a brief description about what each of these concepts entail:
## Tokenization: 
This is used to break down corpus into documents or words.
## Stopwords: 
This is used to eliminate irrelavant words such as He, She, Him, Their etc.
## Stemming: 
it is to reduce words to their base/root word but this may produce some meaningless words due to its mechanism of removing suffixes.
## Lemmatization: 
This is same as stemming but it converts words into their base word that are meaningful.
The use of stemming and lematization depends on the use case whether exact root word needs to be preserved or not.
## Encoding Techniques: 
This is used to convert words into vectors/features
  ## a. Bag of Words(BOW):
  This is one of the techniques to convert words into vectors. However missing semantic meaning and high sparsity are the problems posed by this method.
  ## b. TF-IDF (Term Frequency-Inverse Document Frequency):
  This method can resolve the issue of missing semantic meaning as this captures the semantic meaning or the relation between two words to see if they are semantically similar or not. This help NLP models to determine the context and intent of the text. frequent words have less weightage and rare words have high weightage in this method. The reason being rare words are helpful in distinguishing one sentences from others. Therefore, they are given more weights.
