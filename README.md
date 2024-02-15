## NLP_Sentiment Analysis

<div align="center">
    <img width="500" src="/Images/prom_dic_words.png" alt="Material Bread logo">
     <p style="text-align: center ;">Photo created by autor</p> 
</div>

## Blog explanation:
I've authored a blog detailing the approach I employed to address this sentiment analysis challenge, here I extenisively focus on text preprocessing and the Bag-of-Words (BoW) vectorization techniques.  You can find the article on  my [Medium](https://medium.com/@t.mostafid/exploring-text-preprocessing-and-bow-vectorization-for-nlp-sentiment-analysis-a-case-study-on-16d152000776) profile for further insights.

### Check out article on NLP Sentiment Analysis

## Introduction
This project explores sentiment analysis using NLP,  let's say you have 1,000 product reviews, so pieces of texts written by users. Can you build a system to automatically go through all of these product reviews to figure out what fraction of them are positive reviews versus negative reviews? 

## Dataset
The dataset, [Amazon Fine Food](https://www.kaggle.com/snap/amazon-fine-food-reviews) comprises 568,545 Amazon food reviews spanning a decade, with features such as ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary, and Text.

<div align="center">
    <img width="400" src="/Images/Score_Distribution_1.png" alt="Material Bread logo">
    <p style="text-align: center ;">Photo created by autor</p> 
</div>

## Text Preprocessing, and Feature Engineering

I began by laying the groundwork, delving into EDA, data cleaning, and feature engineering. However, my primary emphasis was on the intricacies of preprocessing. I conducted experiments with four distinct techniques: basic preprocessing, stemming, part-of-speech (POS) tagging, and a combination of all three. Each technique resulted in a separate dataset(list) , which I meticulously fitted and transformed.

To enhance the effectiveness of user reviews, a new feature called "Usefulness" is introduced, considering the ratio of "Helpfulness Numerator" to "Helpfulness Denominator."

## Bag-of-Words(BoW) Vectorization

The BoW model is employed for vectorization, capturing the occurrence of words in the document. The evaluation investigates the impact of different preprocessing steps on the BoW models.


## Evaluation and Findings

In this section, the BoW models of the different preprocessed text data are evaluated and compared.

#### Frequency Vocabulary words

<p align="center">
    <img width="600" src="/Images/word_fre_dic.png" alt="Material Bread logo">
</p> 

This suggests  that **stemming** and **POS tagging** contribute to increased consistency and representative information in the text corpus. 

#### Word Count Used for BoW Models(Total number in the BoW for different preprocessed data)

<p align="center">
    <img width="500" src="/Images/bow_word_count.png" alt="Material Bread logo">
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


<div align="center">
    <img width="500" src="/Images/posneg_entropy.png" alt="Material Bread logo">
    <<p style="text-align: center;">Entropies for positive and negative sentiments. The 100 words with the highest entropy are displayed.</p> 
</div> 


#### Prominent Words in the Vocabulary by Entropy

<p align="center">
    <img width="400" src="/Images/pro_word_entropy.png" alt="Material Bread logo">
<p style="text-align: center;"></p> 



## Conlusion

This Project assesses text preprocessing and the Bag-of-Words (BoW) model for sentiment analysis using the Amazon Fine Food Reviews dataset. The evaluation reveals that incorporating POS tagging and stemming enhances consistency and representative information in the text corpus. However, the BoW model falls short in creating representative and discriminative vectors for sentiment classification due to its reliance on word frequencies, which may not accurately reflect word significance. This limitation is underscored by word entropies in the text samples. To address this, alternative vectorization methods like TF-IDF, which consider word significance, are recommended for future exploration.

Additionally, a substantial imbalance in positive and negative sentiments within the dataset significantly impacts the generation of effective vocabulary for discriminative vectorization, as indicated by the evaluation results. This imbalance should be taken into account in both vectorization and classification model applications in future studies.



## Vader Model, Roberta Model
Additionally, we compare two different models, Vader and Roberta, for analyzing comments on Amazon's fine food dataset. We explore the differences between them and run them on the entire corpus of data, encompassing 500 different reviews from Amazon.



