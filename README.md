# Tweets_SentimentalAnalysis
This contains the code on sentimental analysis on tweets

### About the Dataset: 
Dataset link : https://www.kaggle.com/kazanova/sentiment140

This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment.

It contains the following 6 fields:

target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

ids: The id of the tweet ( 2087)

date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

flag: The query (lyx). If there is no query, then this value is NO_QUERY. user: the user that tweeted (robotickilldozr)

text: the text of the tweet (Lyx is cool)


### Description: 

•	Pre-processsing of text is handled which includes casing, noise removal, tokenization, stop words removal, text normalization(stemming and lemmatization)

•	Tokens are vectorized as machine can only read numerical data 

•	Machine learning algorithm RandomForestClassifier is used for model training

#### Note -- I have just taken very small amount of data for minimizing the computational power. One can use the entire dataset to and train it to increase the accuracy; can even chose a differnt classifier algorithms of your choice

