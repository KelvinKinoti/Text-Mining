# Text-Mining
The purpose of the project is to perform text mining tasks on the given dataset. The project involves several solutions implemented using different packages and techniques.

In Solution 1, the dataset "newsgroups.json" is loaded, and the content field is extracted. A Corpus is created from the text data, and a custom pre-processing function is defined to convert the text to lowercase, remove punctuation, numbers, and stopwords, and stem the words. The pre-processed Corpus is then used to create a document-term matrix (dtm) and a term-document matrix (tdm).

In Solution 2, the LDA (Latent Dirichlet Allocation) model is fit using the dtm. The number of topics is set to 4, and the LDA model is trained. The top 5 terms for each topic are extracted from the model.

In Solution 3, sentiment analysis is performed on the text data. The term-document matrix (tdm) is converted into a matrix, and the word frequencies are calculated. The 5 most frequent words are displayed, and a bar plot is created to visualize the frequencies of the top 5 words.

In Solution 4, the CBOW (Continuous Bag of Words) model is created using the word2vec package. The CBOW model is trained on the newsgroups_text data with specific parameters such as dimension, iteration, and minimum count. The top 5 terms nearest to "can" and "man" are predicted using the trained model.

In Solution 5, the skip-gram model is created using the word2vec package. The skip-gram model is trained on the newsgroups_text data with specific parameters. The top 5 terms nearest to "religion" and "adult" are predicted using the trained model.

Overall, the project aims to explore various text mining techniques and extract insights from the given dataset. It involves tasks such as pre-processing text, topic modeling, sentiment analysis, and word embedding using different approaches and packages.





