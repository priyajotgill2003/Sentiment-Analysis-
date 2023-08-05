
# Money Heist web series Sentiment Analysis
<div align="justify">
This project focuses on performing sentiment analysis of the popular web series Money Heist. The transcripts of each episode were obtained through web scraping from scrapsfromtheloft.com. The analysis consists of several steps, including data scraping, data cleaning, creating a document-term matrix, exploratory analysis, analyzing profanity, sentiment analysis of routines, and topic modeling with text generation using a Markov chain function.
</div>

## Table of Contents
- [Introduction](#introduction)
- [Project Steps](#project-steps)
  - [1. Web Scraping](#1-web-scraping)
  - [2. Data Cleaning](#2-data-cleaning)
  - [3. Document-Term Matrix](#3-document-term-matrix)
  - [4. Exploratory Analysis](#4-exploratory-analysis)
  - [5. Profanity Analysis](#5-profanity-analysis)
  - [6. Sentiment Analysis of Routines](#6-sentiment-analysis-of-routines)
  - [7. Topic Modeling and Text Generation](#7-topic-modeling-and-text-generation)
- [Conclusion](#conclusion)

## Introduction

Money Heist, also known as La Casa de Papel, is a Spanish television series that has gained worldwide popularity. Sentiment analysis helps us understand the emotional tone and sentiments expressed throughout the series. By analyzing the transcripts of each episode, we can gain insights into the overall sentiment, profanity usage, and topics discussed.

## Project Steps

### 1. Web Scraping

The first step involved scraping the data from the website scrapsfromtheloft.com. Using web scraping techniques, we extracted the transcripts of each episode of Money Heist. The scraped data provides the foundation for the subsequent analysis.

<img width="600" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/fec484b1-fe0b-4b3d-90c7-90a69be148c7">


### 2. Data Cleaning

After obtaining the transcripts, we performed data cleaning to remove any irrelevant information, such as HTML tags, special characters, and punctuation. This step ensures that the data is ready for further analysis and prevents any noise from affecting the results.

### 3. Document-Term Matrix

To gain insights into the most common words used in each episode, we created a document-term matrix. This matrix represents the frequency of words across the episodes and allows us to analyze the patterns and identify significant terms.

<img width="600" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/2690cf57-92ec-4c21-a0d6-6258440eaf6a">


### 4. Exploratory Analysis

In this step, we conducted exploratory analysis on the data. We generated word clouds and various graphs to visualize the most common words and their distribution in each episode. These visualizations provide a deeper understanding of the content and help identify key themes and sentiments.

<img width="300" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/80aebaf6-8fc0-407b-aa4d-e1dcbf71076e"> <img width="300" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/06f270ba-e152-46de-b2cc-6bd125df46e9">

<img width="600" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/126951d4-8129-44ba-be54-6189b0218a92">


### 5. Profanity Analysis

We analyzed the amount of profanity present in the transcripts. By using specific techniques or libraries, we calculated the frequency of profane words or phrases. This analysis gives insights into the language usage and intensity of emotions expressed in the series.

<img width="600" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/aff1c8e9-76d6-4276-a558-bd951a2dc659">


### 6. Sentiment Analysis of Routines

To analyze the sentiment of routines, we used sentiment analysis techniques to classify the overall emotional tone of each episode. By examining positive, negative, and neutral sentiments, we can understand the overall mood and emotional journey of the characters throughout the series.

<img width="600" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/2850d69e-3d4f-432d-bb50-7bb06729982f">


### 7. Topic Modeling and Text Generation

In this step, we performed topic modeling on the transcripts.  Additionally, we built a Markov chain function to generate text based on the learned patterns, allowing us to simulate character dialogues or create new scenes.

## Conclusion

This project provides a comprehensive analysis of the web series Money Heist through sentiment analysis, profanity analysis, and topic modeling. By leveraging web scraping, data cleaning, and various analytical techniques, we gain insights into the emotional aspects, language usage, and underlying themes of the series. The findings contribute to a deeper understanding and appreciation of the show.


Considering factors such as profanity usage, explicit content, and intense emotional scenes, the analysis can assist in determining whether the series is suitable for audiences of different age ranges, such as 18+ or mature audiences.
