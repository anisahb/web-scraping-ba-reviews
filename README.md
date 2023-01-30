# web-scraping-ba-reviews

## Introduction
Scraping and analysing customer review data to uncover findings for British Airways. In this notebook, we will scrape reviews on British Airways from the Skytrax website, clean the collected data, and perform data analyses on it. We will use techniques such as topic modelling and sentiment analysis to uncover insights about what customers find important when flying with British Airways.

## Data source:
https://www.airlinequality.com/airline-reviews/british-airway

## Packages used: 
`requests`
`BeautifulSoup` 
`pandas`
`numpy`
`sklearn`
`matplotlib`
`seaborn`
`re`
`wordcloud`
`nltk`
`gensim`
`vaderSentiment`
`textblob`


## Results & Conclusion
The frequency analysis and word cloud are useful to get an overall indication of what words are most prominent in the corpus, and hence which are most important and valuable to customers of British Airways. We then were able to use the LDA for topic modelling, which helped to categorise the words into six topics, from which we can infer a theme of each.

We then used VADER and Text Blob to get an indication of the sentiments, whether they were positive, negative or neutral in the reviews. We visualized these using pie charts, bar graphs and word clouds. Out of the 1000 reviews we analysed, the majority were positive (63.9% from VADER analysis, 68.1% from Text Blob), with positive keywords being related to 'london', 'lounge', 'class', and 'journey'. The negative reviews (32.9% VADER, 28.3% Text Blob) tend to include keywords such as: 'gatwick', 'seat', 'race', and 'crew'.

Themes can be picked out from these analyses and can be used to improve services in the future.
