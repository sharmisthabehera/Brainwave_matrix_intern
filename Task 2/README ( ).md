# TWITTER SENTIMENT ANALYSIS by using NLP

# Dataset Information:

The objective of this task is to detect or judge the sentiment behind the tweets. For the sake of simplicity, we can say a tweet contain both positive and negative tweets i.e., it may be racist or non racist. So, the task is to classify racist or non racist tweets from other tweets.

This dataset is a collection of 31,962 tweets.

# Project Strructure:

1. DATA PREPROCESSING:

The dataset is loaded and the most important part is preprocessing the data, so that the model is ready to be used. Since there are a lots of unnecessary parameters 
in the dataset, so we need to remove it. To remove the unnecessary parameters, I have used the following techniques:
i) Removing Stop Words: Basically words like this, an, a, the, etc., that do not affect the meaning of the tweet
ii) Removing Punctuation: ‘,.*!’ and other punctuation marks that are not really needed by the model
iii) Stemming: Basically reducing words like ‘jumping, jumped, jump’ into its root word (also called stem), which is jump in this case. Since all variations of the root word convey the same meaning, we don’t need each of the word to be converted into different numbers.

2. DATA VIZUALIZATION:

Bar plots has been plotted for top 10 positive & negative hastags for racist/sexist tweets and pie chart for the percentage of positive and negative sentiments.

# Observation:

For Bar plot: 

We have observed that for top 10 positive hashtags for non racist/sexist tweets, 'love' is the highest around 1550 and 'summer' is the lowest around 400. Then for top 10 negative hashtags for racist/sexist tweets, 'trump' is the highest round 130 and 'hate' is the lowest around 40.

For Pie chart:

93% people have negative sentiments or racist/sexist tweets
7% people have positive sentiments or non racist/sexist tweets, so we observed that no.of negative sentiments > no.of positive sentiments

# Conclusion:

Algorithm used is 'Logistic Regression'.             Accuracy Score: 95%

# Contact Information:
Email: sharmisthabehera56@gmail.com           linkedin: www.linkedin.com/in/sharmistha-behera-b704581b6
