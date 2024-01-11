# NLP_Sentiment Analysis

<p align="center">
    <img width="400" src="/Images/title_image.jpg" alt="Material Bread logo">
</p>

## My Medium Articles on NLP Sentiment Analysis

Exploring Text Preprocessing and BoW Vectorization for NLP Sentiment Analysis [Medium](https://medium.com/@t.mostafid/exploring-text-preprocessing-and-bow-vectorization-for-nlp-sentiment-analysis-a-case-study-on-16d152000776)


## Introduction
Sentiment analysis, also known as opinion mining, is a crucial tool in the era of online commerce, cloud-based software solutions, etc. This project explores sentiment analysis using Natural Language Processing (NLP) and computational techniques, focusing on the Amazon Fine Food Reviews dataset.


## Dataset

The dataset, [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews) comprises 568,545 Amazon food reviews spanning a decade, with features such as ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary, and Text.

## Data Cleaning

The dataset underwent cleaning to remove redundancies, resulting in 69.3% of the original reviews for further study.

## Text Preprocessing 

Text preprocessing is a vital step in preparing the reviews for sentiment analysis. This involves removing URLs, HTML tags, punctuation, numeric values, emotions, and special characters. Additionally, stemming and Part-of-Speech (PoS) tagging are applied to refine the processed text.

<p align="Center">
    <img width="300" src="/Images/Score_Distribution_1.png" alt="Material Bread logo">
</p>  

## Feature Engineering

## Sentiment Classification

## Bag-of-Words(BoW) Vectorization

## Evaluation and Findings

## Conclusion and future works

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



