# NLP_Sentiment Analysis

## My Medium Articles on NLP Sentiment Analysis

Exploring Text Preprocessing and BoW Vectorization for NLP Sentiment Analysis [Medium](https://medium.com/@t.mostafid/exploring-text-preprocessing-and-bow-vectorization-for-nlp-sentiment-analysis-a-case-study-on-16d152000776)

This project focuses on sentiment analysis applied to Amazon Fine Food reviews using natural language processing techniques. The primary objective is to conduct a comparative analysis of two widely used sentiment analysis methods. Additionally, the project aims to develop an effective model for discerning whether a review conveys a positive or negative sentiment based on its textual content.

<p align="center">
    <img width="400" src="/Images/title_image.jpg" alt="Material Bread logo">
</p>

## What is Sentiment Analysis?

Sentiment analysis is the process of identifying the emotional tone conveyed in a text. A sentiment classification model takes a given text as input and produces probabilities for whether the sentiment expressed is positive, negative, or neutral. This analytical approach finds application in categorizing customer reviews across various online platforms.

## Objective

The objective is to given a review is positive (rating of 4or 5) or negative (rating of 1 or 2)


## DataSet

The dataset, [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews), consists of reviews of fine foods from Amazon. While the dataset spans over 10 years with approximately 500,000 observations, we performed sentiment model comparison on a subset of 500 observations for speed. However, for prediction purposes, the 100,000 observation was used.

## Imbalance distribution of Scores by Stars(Rating)

The uneven distribution of instances across different classes represents the imbalance in the target variable (score). The main concern associated with unbalanced datasets is the potential bias introduced in machine learning models, giving preference to the majority class and resulting in less effective performance, especially for the minority classes. In this scenario, Score 2 and Score 3 represent the minority classes.

<p align="Center">
    <img width="300" src="/Images/Score_Distribution_1.png" alt="Material Bread logo">
</p>  

## Distribution of word count by Scores


<p align="center">
    <img width="400" src="/Images/word_count.png" alt="Material Bread logo">
</p>


The plot shows that usually for very positive and very negative commnets shorter texts are written, while for the middle rate (3) the comments are the longest (probably users write both positive and negative aspects.)

## Dictionary word Frequencies

<p align="center">
    <img width="800" src="/Images/word_fre_dic.png" alt="Material Bread logo">
</p>  

## Methodology for Determining Review Sentiment:

We will use the provided Score/Rating for classification. A rating of 4 or 5 will be categorized as a positive review, while a rating of 1 or 2 will be considered negative. Reviews with a rating of 3 will be treated as neutral and excluded from our analysis. This approach serves as an approximate and proxy method for assessing the polarity (positivity/negativity) of a review.


## Vader Model, Roberta Model
Additionally, we compare two different models, Vader and Roberta, for analyzing comments on Amazon's fine food dataset. We explore the differences between them and run them on the entire corpus of data, encompassing 500 different reviews from Amazon.



