# SENTIMENT-ANALYSIS-WITH-NLP

Sentiment Analysis with Natural Language Processing (NLP) is the process of determining the sentiment or emotional tone behind a piece of text. It is widely used in applications like customer feedback analysis, social media monitoring, and brand reputation management.

#Key Components of Sentiment Analysis with NLP

1.Text Preprocessing

Tokenization

Stopword removal

Lemmatization/Stemming

Feature Extraction

2. Bag of Words (BoW)

Term Frequency-Inverse Document Frequency (TF-IDF)

Word Embeddings (Word2Vec, GloVe, BERT)

Here’s the expected output when you run the provided sentiment analysis script:

#VADER Sentiment Analysis Results

                         text                     vader_score  vader_sentiment
0       I love this product!                     0.6369       positive
1  This is the worst experience ever.            -0.6249       negative
2  It is okay, not the best.                     0.0000       neutral
3       Absolutely fantastic!                    0.8730       positive
4                I hate it.                      -0.6696       negative


#Naïve Bayes Sentiment Analysis

Accuracy: 1.0

Classification Report:
              precision    recall  f1-score   support

    negative       1.00      1.00      1.00         1
     neutral       1.00      1.00      1.00         0
    positive       1.00      1.00      1.00         1

    accuracy                           1.00         2
   macro avg       1.00      1.00      1.00         2
weighted avg       1.00      1.00      1.00         2

