# NLP_SentimentAnalysis

## Overview

This project's main goal is to perform sentiment analysis on Amazon Fine Food reviews, utilizing natural language processing techniques. The primary focus includes a comparative analysis of two widely used sentiment analysis methods. Additionally, the project aims to develop a model that can effectively discern whether a review conveys a positive or negative sentiment based on its textual content.


<p align="center">
    <img width="400" src="sentiment_analysis.webp" alt="Material Bread logo">
</p>

## What is Sentiment Analysis?
Sentiment analysis involves ascertaining the **emotional tone conveyed in a piece of text**. Typically, a sentiment classification model takes a text input and outputs the probability of the expressed sentiment being positive, negative, or neutral.

The application of sentiment analysis extends to categorizing customer reviews on diverse online platforms.


## DataSet
The Dataset  [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews) consists of reviews of fine foods from Amazon. 

This data was acquired over a period of more than 10 years(~500,000 Observations), but in this project, for the sake of speed, we analyzed 500 observations.
Reviews Include rating, user information, plaintext, etc.


## Objective
Our Objective is to determine the sentiment of a review; we analyze the provided rating and classify it as positive (if the rating is 4 or 5) or negative (if the rating is 1 or 2).


## Vader Model, Roberta Model
For Sentiment Analysis, we apply two different models (Vader and Roberta model) for reviewing the comments on Amazon's fine food dataset.
We Explored the differences between them and ran them on a whole corpus of data with 500 different reviews from Amazon.




