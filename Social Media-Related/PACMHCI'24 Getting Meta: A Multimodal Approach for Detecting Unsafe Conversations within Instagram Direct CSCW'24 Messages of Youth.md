# Getting Meta: A Multimodal Approach for Detecting Unsafe Conversations within Instagram Direct Messages of Youth 


**Link:** [https://dl.acm.org/doi/pdf/10.1145/3579608](https://dl.acm.org/doi/pdf/10.1145/3579608)


**Journal:** PACMHCI
**Keywords:** : online risk detection, machine learning, ensemble models, social media, Instagram, end-to-end encryption


### Summary

This work developed an automated multimodal approach utilizing metadata, linguistic cues, and image features to detect and classify risky conversations. It demonstrated that metadata can effectively be utilized for detecting risky conversations, while also showcasing that both linguistic cues and images can enhance the detection and classify different risky categories.


### Pros
1. Detailed and comprehensive comparison experiments.
2. A good entry point focusing on youths.
3. High data set quality and protect participants well.
4. Detailed, comprehensive, and convincing qualitative analysis and case studies.
5. Work well on data balance.

### Cons
1. Text classifiers seem weak, BERT and related language models might perform better.
2. Not only screenshots contain meaningful text and worth OCR. Text in other kinds of images may need to be considered as well.

### My Reflection
My previous work on detecting Illicit Promotional Content on Chinese TikTok leveraged similar tech stacks as this work, but not as good as it. After reading this paper, I realized my work's shortages.
1. Data. The selected data of my work were not representative and I did not do well on data balance.
2. Metadata. Although I used some metadata, I didn't consider them as features.
3. Case study and qualitative analysis. Not as detailed and diverse as this work.
4. Too heavy. My work cost too much computational resources due to language model and vision model. Machine Learning algorithms can be used for lightweight.

## Paper Details
### Abstract
Instagram is widely used with a high impact and user population, especially among teenagers and young adults. It also has a negative influence on users. To defend against malicious actors, HCI and AI researchers build automated risk detection systems, but they face 2 challenges: 

1. Absence of ecologically valid datasets specific to youth; over-focus on publicly available data rather than private messages, which contain more risky interactions. They over-rely heavily on third-party annotators instead of victims, and most approaches are based on textual features.
2. Challenge of analyzing multimodal data (cannot access insta's end-to-end encryption)

Solution 1: Multimodal data. Select representative data and label it by the participants themselves.
Solution 2: Use metadata features like the number of messages that are exchanged in a conversation, their inter-arrival time, and the direction of the message.

### Research Question
RQ1: Can we identify unsafe conversations from safe ones using metadata features. Are linguistic and image features necessary?
RQ2: Can we accurately detect the types of risks presented in an unsafe conversation?



### Data
28,725 conversations containing approximately 5 million Instagram private messages collected from 172 teens and young adults who are aged 13-21.

### Findings
1. With testing the classifiers,  in the presence of end-to-end encryption conversation-level characteristics could still allow platforms to detect risk and protect their users
2. Meta-level features based on the conversation structure (i.e., the number of users in the conversation, the length of the conversation, etc.) can detect unsafe conversations; the content of these conversations (i.e., linguistic and image features) can differentiate between different risk types


### Novelty
1. The data were labeled by the participants themselves which is more accurate.
2. Built an end-to-end multimodal approach that combines multiple heterogeneous modalities (metadata, linguistic cues, and image features) for the detection of unsafe conversations and risk types in the unsafe conversations.


### Method
1. Towards RQ1, this work builds separate classifiers based on metadata, linguistic cues, and images, respectively. Combine them as an ensemble classifier.
2. Towrds RQ2, the top five most frequently occurring risks were picked and classified with the same features.


### Conclusion
1. Meta-level data is a better predictor of conversational-level risk than contextual data contained within the messages themselves. It means: 1. lightweight, lighter than NLP/Vision analysis 2. User data protection-friendly.
2. Content of linguistic cues and images can enhance the result of meta-level classifiers and be nuanced to distinguish different risks.