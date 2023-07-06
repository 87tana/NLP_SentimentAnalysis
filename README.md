# NLP_SentimentAnalysis


<p align="center">
    <img width="400" src="sentiment_analysis.webp" alt="Material Bread logo">
</p>

## What is Sentiment Analysis?

Sentiment analysis is the process of determining the sentiment intent of the text.

Generally, the input to a sentiment classification model is a piece of text, and the output is the probability that the sentiment expressed is positive, negative, or neutral.

Sentiment analysis is used to classify customer reviews on various online platforms.


## DataSet
The Dataset  [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews) consists of reviews of fine foods from Amazon. 

This data was acquired over a period of more than 10 years(~500,000 Observations), but in this project, for the sake of speed, we analyzed 500 observations.
Reviews Include rating, user information, plaintext, etc.


## Objective
Our Objective is to determine the sentiment of a review; we analyze the provided rating and classify it as positive (if the rating is 4 or 5) or negative (if the rating is 1 or 2).


## Vader Model, Roberta Model
For Sentiment Analysis, we apply two different models (Vader and Roberta model) for reviewing the comments on Amazon's fine food dataset.
We Explored the differences between them and ran them on a whole corpus of data with 500 different reviews from Amazon.




