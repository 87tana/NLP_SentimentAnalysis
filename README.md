# NLP_Sentiment Analysis (under constructions :) )

This project focuses on sentiment analysis applied to Amazon Fine Food reviews using natural language processing techniques. The primary objective is to conduct a comparative analysis of two widely used sentiment analysis methods. Additionally, the project aims to develop an effective model for discerning whether a review conveys a positive or negative sentiment based on its textual content.

<p align="center">
    <img width="400" src="/Images/OIP.jpg" alt="Material Bread logo">
</p>

## What is Sentiment Analysis?

Sentiment analysis is the process of identifying the emotional tone conveyed in a text. A sentiment classification model takes a given text as input and produces probabilities for whether the sentiment expressed is positive, negative, or neutral. This analytical approach finds application in categorizing customer reviews across various online platforms.

## Objective

The objective is to given a review is positive (rating of 4or 5) or negative (rating of 1 or 2)


## DataSet

The dataset, [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews), consists of reviews of fine foods from Amazon. While the dataset spans over 10 years with approximately 500,000 observations, we performed sentiment model comparison on a subset of 500 observations for speed. However, for prediction purposes, the 100,000 observation was used.

## Distribution of Scores

<p align="center">
    <img width="300" src="/Images/Score_Distribution.png" alt="Material Bread logo">
</p>  


## Generating BoW model

Generate BoW model for the four preprocessed datasets.


## Dictionary word Frequencies

## Methodology for Determining Review Sentiment:

We will use the provided Score/Rating for classification. A rating of 4 or 5 will be categorized as a positive review, while a rating of 1 or 2 will be considered negative. Reviews with a rating of 3 will be treated as neutral and excluded from our analysis. This approach serves as an approximate and proxy method for assessing the polarity (positivity/negativity) of a review.


## Vader Model, Roberta Model
Additionally, we compare two different models, Vader and Roberta, for analyzing comments on Amazon's fine food dataset. We explore the differences between them and run them on the entire corpus of data, encompassing 500 different reviews from Amazon.



