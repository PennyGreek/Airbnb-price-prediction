# Supercar Fans Twitter Data Analysis
This analysis primarily centers around real-time electronic Word-of-Mouth (eWOM) occurring on Twitter during Supercar broadcasts, with the aim of extracting valuable insights and offering managerial recommendations to event organizers. 
The focus of this analysis is to understand the content of live tweets and their influence on user engagement and TV ratings for Supercar events. To achieve this, the analysis is structured into four key components, each aimed at addressing specific questions and shedding light on this critical aspect of Supercar events.
## Key Questions Addressed
This analysis seeks to address the following essential questions:
## Main Topics: What are the primary themes and subjects of tweets during Supercar events?
(using the LDA model)

## Sentiments: What are the sentiments and emotions conveyed in these main topics?
(using NLTK (Natural Language Toolkit) open-source Python package with the VADER (Valence Aware Dictionary and sentiment Reasoner) tool. VADER is a lexicon and rule-based tool that is specifically tuned to analyze the sentiments expressed in social media)

Classify the tweets based on the scores that the tools/packages provide:
>= 0.05 POSITIVE
> -0.05 & < 0.05 NEUTRAL
<= -0.05 NEGATIVE

## Impact on Engagement: How does the content of live tweets influence online user engagement and TV ratings? 
(using linear regression model)

## Recommendations: What actionable steps can Supercar event organizers take to enhance their business performance? 
(based on the conclusion and EDA )
