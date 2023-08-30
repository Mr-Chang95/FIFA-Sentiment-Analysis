# 2022 FIFA World Cup: Sentiment Analysis with RoBERTa and RNN(LTSM)

![soccer2](https://github.com/Mr-Chang95/FIFA-Sentiment-Analysis/assets/92649864/b0a7e7ac-3445-4e60-baeb-26ce85bec7e0)

## About Dataset
Football is one of the most loved sports worldwide. The FIFA World Cup, a global football sporting event that takes place every four years, is in Qatar in the year, 2022. This dataset contains 30,000 tweets from the first day of the FIFA World Cup 2022 and primarily contains tweets in English containing the hashtag #WorldCup2022.

This dataset contains tweets about FIFA World Cup 2022 from Twitter. This dataset includes features such as Date Created, Number of Likes, Source of Tweet, Tweet, Sentiment.  

## Business Understanding

**Objective**

The objective of this data science project is to conduct sentiment analysis on tweets related to the FIFA World Cup 2022. By analyzing the sentiment of tweets, the project aims to gain insights into the public's perception, emotions, and opinions surrounding the event. This information can be leveraged by various stakeholders, including event organizers, sponsors, and marketing teams, to make informed decisions and enhance user engagement.

**Key Stakeholders:**

- Event Organizers: The FIFA World Cup organizers can use sentiment analysis to gauge the overall sentiment of fans, identify potential issues, and ensure a positive experience during the event.

- Sponsors: Sponsors can monitor sentiment to understand the effectiveness of their campaigns and brand perception among fans.

- Marketing Teams: Marketing teams can adjust their strategies in real-time based on the sentiment analysis results to maximize engagement and reach.

## What I did in this project
1. Data Preprocessing:

    - Each tweet's text will undergo a meticulous preprocessing phase:
    - Tokenization: Breaking down text into individual words.
    - Cleaning: Removal of stopwords, URLs, mentions, and hashtags.
    - Normalization: Applying stemming or lemmatization techniques to standardize words, ensuring consistency in sentiment analysis.

2. Data Visualization:

    - Harnessing the power of data visualization, the project will render sentiment insights into tangible and easily digestible formats.
    - Sentiment distribution plots, word clouds of positive and negative words, and time series sentiment trends during the event will be constructed, enabling stakeholders to glean insights at a glance.

3. Sentiment Analysis:

    - The project will employ a sophisticated sentiment analysis model, such as the VADER framework, or alternatively, a machine learning model trained on sentiment-labeled datasets.
    - By leveraging these models, sentiment scores will be calculated for each tweet, encompassing dimensions of positivity, negativity, neutrality, and an overall sentiment compound score. Some models that I used are the RoBERTa and XGBoost models, as well as creating a Neaural Network(LTSM).
  
4. Insights and Reporting:

    - Comprehensive sentiment trend analyses will be performed, unveiling the ebb and flow of public sentiment across the duration of the World Cup.
    - By correlating sentiment trends with specific event occurrences such as matches, goals, controversies, and celebratory moments, stakeholders will be equipped with actionable insights.

## Acknowledgement 
This dataset was downloaded from Kaggle. In future World Cups, I plan to scrap data from Twitter(now X), using their API.