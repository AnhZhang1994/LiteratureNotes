# [COVIDSenti: A Large-Scale Benchmark Twitter Data Set for COVID-19 Sentiment Analysis](https://ieeexplore.ieee.org/document/9340540)

**Link:** [https://ieeexplore.ieee.org/document/9340540](https://ieeexplore.ieee.org/document/9340540)


**Journal:** IEEE Transactions on Computational Social Systems 2021

**Keywords:** COVID-19, Twitter, ML


## My notes
### Summary
This paper proposed a Twitter sentiment dataset, makes tweet sentiment classifiers with ML, extracts indicative topics, and tests SOTA ML classification mechanisms.
**Related Technique:** ML, DL, NLP

### Pros
1. Comperehensive comparison experiments.

### Cons
1. Technical parts are not detailed and confusing. Not convicing either.
2. The method of semantic classification for dividing the data into pos/neg/neutural is not convicing


## Details
### Abstract
This paper collected Twitter data using the Twitter API from February to March 2020, and sentiment identified from the collected tweets was labeled into three categories: those containing positive, negative, and neutral tweets. Different algorithmic models are used to train and validate the data set to provide the baselines for detecting sentiment related to prospective COVID-19 treatments spread on Twitter. Through a final verification analysis, the best performing model is selected to optimize and promote. 


### Data
90,000 tweets from 210 million tweets with Tweepy.

### Technique
1. Sentiment analysis with TextBlob to divide the data into positive, negative, and neutral
2. Topic model (LDA) to extract topics.
3. Feature extraction with vectorization techniques (TF-IDF) and word embeddings (pretrained Word2Vec, GloVe, and fastText embeddings trained on Common Crawl and Wikipedia)
4. Classification with different models
### Conclusion

1. Bert performs the best among selected mechanisms.
2. In Feb, people supported the lockdown and stay home order, but they shiffted in March. It might be related to misinformation.
