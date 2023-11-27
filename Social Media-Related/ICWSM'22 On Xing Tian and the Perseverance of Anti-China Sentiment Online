# [On Xing Tian and the Perseverance of Anti-China Sentiment Online](https://publications.cispa.saarland/3641/)
**Conference:** ICWSM 2022
**Keywords:** Sinophobia, Hate Speech, Social Media, NLP

## My notes
### Summary
Measure sinophbia by analyzing posts from Reddit and 4chan /pol/ from 2016 to 2021, this paper found and proved anti-Chinese content may be avoked by political events not directly related to China and how anti-Chinese sentiment evolved

**Related Technique:** crawler/scrapper, word2vec, similarity calculation, data visualization, topic model

### Pros
1. Hot topic from special perspectives (hatespeech and conspiracy theories) target to sinophobic
2. Comperehensive intuitive visualization
3. Comperehensive investigation with NLP technique (word2vec and topic model)


### Cons
1. Quite similar to [“Go eat a bat, Chang!”: On the Emergence of Sinophobic Behavior on Web Communities in the Face of COVID-19](https://dl.acm.org/doi/10.1145/3442381.3450024)
2. The paper does not explain why they adopted techniques they used and advantages compared with other techniques (e.g. transformer, bert)

## Details

### Abstract
Sinophobia is an existing problem, this paper analyzes  andquantifies Sinophobic behaviors with regard to its origins, evolution, and content from posts on Reddit and 4chan /pol/.
### Findings
1. Temporal patterns of China-related posts
2. Discover Sinophobic slurs
3. Prove Sinophbia has been common since long long ago, got much more furious since Covid, and can be triggered by non-China related political events.

### Data
1. 4chan /pol/: collected with offical API, 206,329,393 posts between June 30, 2016 to March 18, 2021
2. Reddit: collected with [Pushshift](https://ojs.aaai.org/index.php/ICWSM/article/view/7347), 8,118,465,218 posts between June 1, 2016 and March 31, 2021

### Technique
1. Train a word2vec model to discover slurs
2. To verify the tendency relationship between the term
“china”, “chinese”, and slur words in a quantitative way,
we measure the correlation coefficient of them in different
periods with Pearson correlation.
3. Sentiment analysis with Google Perspective API
4. Train word2vec models on every month's data to measure semantic evolution of shifting of "China" and "Chinese".
5. Topic model (tio2vec) to extract topics.
### Conclusion
This study tracks the evolution of online Sinophobia from 2016 to 2021 on Reddit and 4chan's /pol/. It found that Sinophobia existed before COVID-19, driven by political events. The pandemic heightened online Sinophobia, changing how "China" and "Chinese" were referenced towards using derogatory terms. Ethnicity-related topics overlapped between platforms, but Reddit also had lighter topics like food. Despite COVID-19 intensifying Sinophobia, it was already a prevalent topic online.