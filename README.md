# NLP_Sentiment Analysis

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

This data was acquired over a period of more than 10 years(~500,000 Observations),for the sentiment models comparison , for the sake of speed, we analyzed 500 observations. but for prediction purposes  the whole data were used to analyzed.

## Attribute Information:

**Id**


**ProductId** - unique identifier for the product


**UserId** : unqiue identifier for the user


**ProfileName**


**HelpfulnessNumerator** :number of users who found the review helpful


**HelpfulnessDenominator** : number of users who indicated whether they found the review helpful or not


**Score** : rating between 1 and 5


**Time** : timestamp for the review


**Summary** : brief summary of the review


**Text** : text of the review

## Objective

The objective is to classify reviews as either positive (rated 4 or 5) or negative (rated 1 or 2).

## Methodology for Determining Review Sentiment:

We will utilize the provided Score/Rating for the classification. A rating of 4 or 5 will be categorized as a positive review, while a rating of 1 or 2 will be considered negative. Reviews with a rating of 3 will be treated as neutral and excluded from our analysis. This approach serves as an approximate and proxy method for assessing the polarity (positivity/negativity) of a review.


## Vader Model, Roberta Model
In addition, we compare two different models (Vader and Roberta model) for reviewing the comments on Amazon's fine food dataset.
We Explored the differences between them and ran them on a whole corpus of data with 500 different reviews from Amazon.




