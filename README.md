# NLP project- Text Summarization for Sentiment Analysis

## Intro:
For the final project, I would like to create a text summarization model that also
accurately captures the sentiment of the text. Which means that, ideally, the sentiment analysis of
the summarized text should have a similar or even better performance than the sentiment analysis
performed on the entire text. I chose this topic because both sentiment and the context of the
sentiment are useful for consumers to determine if they want to purchase the product based on
the review, and not all text summarization does a good job capturing the sentiment of the text.

## Data
The dataset I am using for this project is the Amazon Kindle Book Review Data. It is a
small subset of the dataset of Book reviews from the Amazon Kindle Store category. 5-core
dataset of product reviews from Amazon Kindle Store category from May 1996 - July 2014. The
small version of the data contains a total of 12000 entries. Each reviewer has at least 5 reviews
and each product has at least 5 reviews in this dataset. For simplicity, I created the sentiment
label for the reviews by labeling review score 3 and above as positive, and below 3 as negative.
The positive sentiment is represented by 1 and the negative sentiment is represented by 0, there
are 8000 positive comments and 4000 negative comments after the transformation. Then I
divided the data into 80% training data and 20% testing data for training the sentiment analysis
model.

[https://www.kaggle.com/datasets/meetnagadia/amazon-kindle-book-review-for-sentiment-analysis]
