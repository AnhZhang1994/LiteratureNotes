# Sliding into My DMs: Detecting Uncomfortable or Unsafe Sexual Risk Experiences within Instagram Direct Messages Grounded in the Perspective of Youth 


**Link:** [https://scholar.google.com/citations?view_op=view_citation&hl=en&user=sV43f5AAAAAJ&sortby=pubdate&citation_for_view=sV43f5AAAAAJ:hFOr9nPyWt4C](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=sV43f5AAAAAJ&sortby=pubdate&citation_for_view=sV43f5AAAAAJ:hFOr9nPyWt4C)


**Conference:** Proceedings of the ACM on Human-Computer Interaction
**Keywords:** Online Safety, Youth Online Risks, Machine Learning, Deep Learning


## My notes
### Summary
Use CNN and ML to detected sexual risks in insta DM conversations and train a classifier to identify the risky level. Measurement, qualitative analysis, and case studies on results.
**Related Technique:** ML, DL, NLP

### Pros
1. Focus on a minor group lacking attention
2. Carefully selected data
3. Comprehensive benchmark comparison experiments
4. Nice detailed and comprehensive qualitative analysis and case studies

### Cons
1. It might be better if language models can be set in comparison experiments
2. Other cons are mentioned in the "limitation and future work" section

## Details
### Abstract
• RQ1: Based on the first-person accounts of youth, what attributes can help us best predict
whether sexual risk is present within a private social media conversation?

• RQ2: a) Can we accurately predict if a given message is sexually risky? b) If so, can we assess
its risk severity level?

• RQ3: a) How are the contextual, linguistic, and semantic features most predictive of sexual risk
inform our understanding of the sexual risk behaviors of youth online? b) What are the most
common reasons for misclassifications?

### Data
15,547 instagram DM conversations from 150 filtered adolescents
PAN12 as a baseline

### Findings
1.  Overall, we observed that all traditional classifiers had the best performance with the combination of features (LIWC, Sentiment, TF-IDF, and Sexual Lexicons) plus contextual factors (age, gender, and relationship), compared to having features separately or the combination of features without the contextual features

2. Both yes. For binary classification, CNN and RF performed better in conversation-level. For risky level, the CNN classifier outperformed SVM, RF, and LR.

3. Refer to case studies for details.




### Conclusion
The first work that analyzes machine learning approaches on private social media conversations of youth to detect unsafe sexual conversations. In addition, this work highlights the importance of contextual and implicit features on identifications of unsafe sexual conversations and provides a good indication of how different methods and features perform when addressing this problem. 