# [“Go eat a bat, Chang!”: On the Emergence of Sinophobic Behavior on Web Communities in the Face of COVID-19](https://dl.acm.org/doi/10.1145/3442381.3450024)

**Keywords:** COVID-19, Sinophobia, Hate Speech, Twitter, 4chan


## Abstract
Target to the spread of COVID-19, to keep social distance, online medium became more active, but with spreading potentially harmful and disturbing content (e.g.  conspiracy theories and hateful speech).

We collected and analyzed 2 larrge datasets from Twitter and 4chan (time period: 5 months) to investigate whether there is a rise or important differences with regard to the dissemination of Sinophobic content. 

As a conclusion, COVID-19 boosted Sinophobia online and it is a cross-platform pheomenon (from fringe web communities like /pol/ ( "Politically Incorrect") to mainstream platforms like Twitter).


### Findings
1. Discussions related to China and Chinese people on Twitter and 4chan's /pol/ after the outbreak of the COVID-19 pandemic raised. The increase in these discussions and Sinophobic slurs coincides with real-world events related to the COVID-19 pandemic. 
2. With word embeddings, we find that various racial slurs are used in these contexts on both Twitter and /pol/ which shows it is a cross-platform phenomenon.
3. Analyzing word embeddings over time, we discover new emerging slurs and terms related to Sinophobic behavior, as well as the COVID-19 pandemic (e.g. asshoe, Kungflu).
4. By comparing data before and after COVID-19 outbreak, we observe shifts in the content posted by users on Twitter (towards blaming China and Chinese people) and /pol/ (towards using more and new Sinophobic slurs.).

### Data
1. **Twitter:**  
Collection Tool: Streaming API
Time Period: 1 Nov 2019 - 22 Mar 2020
Amount: 222,212,841 tweets (English only)

2. **4chan /pol/:**
Collection Tool: [JsonAPI](shttps://github.com/4chan/4chan-API)
Time Period: 1 Nov 2019 - 22 Mar 2020
Amount: 16,808,191 posts.


### Temporal Analysis
**1. The rises on 4chan match the real-world major events**
```Mentions of the terms “china” and “chinese” on 4chan's /pol/```

![Mentions of the terms “china” and “chinese” on 4chan's /pol/.](https://dl.acm.org/cms/attachment/f71c0ed8-ad28-404a-b08b-8bc9c250df00/www21-239-fig1.jpg)

```Major events```
| #   | Date       | Event                                                    |
| --- | ---------- | -------------------------------------------------------- |
| 1   | 2019-12-12 | President Donald Trump signs an initial trade deal with China. |
| 2   | 2020-01-23 | The Chinese government announces a lock-down in Wuhan. |
| 3   | 2020-01-30 | The World Health Organization declares a public health emergency]. |
| 4   | 2020-02-23 | 11 municipalities in Lombardy, Italy are locked down [19]. |
| 5   | 2020-03-09 | Italy extends restrictions in the northern region of the country. |
| 6   | 2020-03-16 | Donald Trump referred to COVID-19 as “Chinese Virus” on Twitter. |

**2. Twitter discussion during the first peak is significantly lower than when Europe gets involved, possibly due to Twitter's broader geographic reach or /pol/'s susceptibility to conspiracy and racism-related posts on 4chan.**
```Mentions of the terms “china” and “chinese” on Twitter.```
![Mentions of the terms “china” and “chinese” on Twitter.](https://dl.acm.org/cms/attachment/7ba949bd-303b-46c6-87bc-c64c2a2efdae/www21-239-fig2.jpg)

**3. Temporal dynamics of Sinophobic racial slurs on 4chan's /pol/ and Twitter**

Slur pick: "chink,” “bugland,” “chankoro,” “chinazi,” “gook,” “insectoid,” “bugmen,” and “chingchong”

```Mentions of Sinophobic racial slurs on 4chan's /pol/.```
![Mentions of Sinophobic racial slurs on 4chan's /pol/.](https://dl.acm.org/cms/attachment/559d80e0-8a0d-4e26-83a7-de7cfb8d5cd5/www21-239-fig3.jpg)

```Mentions of Sinophobic racial slurs on Twitter.```
![Mentions of Sinophobic racial slurs on Twitter.](https://dl.acm.org/cms/attachment/227a036a-c1e0-4267-84dd-b1ffb61757f1/www21-239-fig4.jpg)

```Top 20 most similar words, along with their cosine similarities, to the words “china,” “chinese,” and “virus” obtained from the word2vec models trained for the whole period (November 2019 - March 2020).```

![Top 20 most similar words, along with their cosine similarities, to the words “china,” “chinese,” and “virus” obtained from the word2vec models trained for the whole period (November 2019 - March 2020).](image/4chantwitterwrod2vec.png)

#### Takeaway of Temporal Analysis
1. 4chan and Twitter are heavily discussing China in relation to COVID-19, and that this discussion accelerated rapidly once the Western world became affected.
2.  Differences in the use of slurs on /pol/ and Twitter.

## Content Analysis
Technique: word2vec (skip-gram)
Method: 3 groups of word2vec models for each of Twitter and /pol/: