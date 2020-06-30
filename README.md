# Sentiment-Analysis--Movie-Reviews

Using NLP sentiment analysis on dataset of 25,000 movie reviews to figure out
their overall sentiment and match it to a value of 0 or 1. O means that the
movie review had an IMDB rating of < 5 (negative rating), and 1 means it was greater (relatively positive).

In this model, preprocessed data by removing HTML tags, stopwords, and numbers. Then, implemented countvectorizer to form bag of words. Used RandomForestClassifier on Bag of words of length 4000
