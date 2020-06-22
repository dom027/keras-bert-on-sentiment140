# keras-bert-on-sentiment140

Implementation of the BERT on the sentiment140 dataset.

## Sentiment140 
The sentiment140 dataset contains 1.6 million tweets extracted using the twitter api. The tweets have been annotated (0 = negative, 2 = neutral, 4 = positive) and they can be used to detect sentiment. 

It contains the following 6 fields:
- target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
- ids: The id of the tweet ( 2087)
- date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- flag: The query (lyx). If there is no query, then this value is NO_QUERY.
- user: the user that tweeted (robotickilldozr)
- text: the text of the tweet (Lyx is cool)

For more details and downloads of the dataset, please visit https://www.kaggle.com/kazanova/sentiment140.

## Pre-trained BERT Models
In this project, we fine-tuned our model on the base of the "uncased_L-4_H-512_A-8" pre-trained model from Google Research Team. Till March 11th, 2020, 24 BERT pre-trained models were released. Their github page can be visited from https://github.com/google-research/bert.
