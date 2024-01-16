## NLP_Sentiment Analysis

<div align="center">
    <img width="300" src="/Images/title_image.jpg" alt="Material Bread logo">
     <p style="text-align: center ;">Photo created by autor</p> 
</div>

### Check out my [Medium](https://medium.com/@t.mostafid/exploring-text-preprocessing-and-bow-vectorization-for-nlp-sentiment-analysis-a-case-study-on-16d152000776) article on NLP Sentiment Analysis

## Introduction
Sentiment analysis, also known as opinion mining, is a crucial tool in the era of online commerce, cloud-based software solutions, etc. This project explores sentiment analysis using Natural Language Processing (NLP) and computational techniques, focusing on the Amazon Fine Food Reviews dataset.


## Dataset

The dataset, [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews) comprises 568,545 Amazon food reviews spanning a decade, with features such as ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary, and Text.

<div align="center">
    <img width="300" src="/Images/Score_Distribution_1.png" alt="Material Bread logo">
    <p style="text-align: center ;">Photo created by autor</p> 
</div>

## Data Cleaning and Text Preprocessing 
The dataset underwent cleaning to remove redundancies, resulting in 69.3% of the original reviews for further study.

Text preprocessing is a vital step in preparing the reviews for sentiment analysis. This involves removing URLs, HTML tags, punctuation, numeric values, emotions, and special characters. Additionally, stemming and Part-of-Speech (PoS) tagging are applied to refine the processed text.

## Feature Engineering

To enhance the effectiveness of user reviews, a new feature called "Usefulness" is introduced, considering the ratio of "Helpfulness Numerator" to "Helpfulness Denominator."

## Sentiment Classification

Sentiments are classified into positive, negative, and neutral categories based on the review scores.

## Bag-of-Words(BoW) Vectorization

The BoW model is employed for vectorization, capturing the occurrence of words in the document. The evaluation investigates the impact of different preprocessing steps on the BoW models.


## Evaluation and Findings

In this section, the BoW models of the different preprocessed text data are evaluated and compared.

#### Frequency Vocabulary words

<p align="center">
    <img width="400" src="/Images/word_fre_dic.png" alt="Material Bread logo">
</p> 

This suggests  that **stemming** and **POS tagging** contribute to increased consistency and representative information in the text corpus. 

#### Word Count Used for BoW Models(Total number in the BoW for different preprocessed data)

<p align="center">
    <img width="400" src="/Images/bow_word_count.png" alt="Material Bread logo">
</p> 

#### Prominent Words in the Vocabulary

<p align="center">
    <img width="400" src="/Images/prom_dic_words.png" alt="Material Bread logo">
</p> 

 Tagging nouns, adjectives, verbs, and adverbs along with stemming results in a vocabulary that is intuitively more appropriate to represent the sentiments of the text.

#### Frequency of the Vocabulary Words for Sentiment

<p align="center">
    <img width="400" src="/Images/posneg_dic_words.png" alt="Material Bread logo">
</p> 


#### Entropy of Vocabulary Words for Sentiments


<p align="center">
    <img width="400" src="/Images/posneg_entropy.png" alt="Material Bread logo">
</p> 


#### Prominent Words in the Vocabulary by Entropy

<p align="center">
    <img width="400" src="/Images/pro_word_entropy.png" alt="Material Bread logo">
</p> 



## Vader Model, Roberta Model
Additionally, we compare two different models, Vader and Roberta, for analyzing comments on Amazon's fine food dataset. We explore the differences between them and run them on the entire corpus of data, encompassing 500 different reviews from Amazon.



