# Sentiment Analysis on Web Series Money Heist

This project focuses on performing sentiment analysis on the popular web series Money Heist. The transcripts of each episode were obtained through web scraping from scrapsfromtheloft.com. The analysis consists of several steps, including data scraping, data cleaning, creating a document-term matrix, exploratory analysis, analyzing profanity, sentiment analysis of routines, and topic modeling with text generation using a Markov chain function.

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
<img width="973" alt="image" src="https://github.com/priyajotgill2003/Sentiment-Analysis-/assets/72308930/8c11de0c-f6a6-45d1-8dce-b773ce2f0946">


### 2. Data Cleaning

After obtaining the transcripts, we performed data cleaning to remove any irrelevant information, such as HTML tags, special characters, and punctuation. This step ensures that the data is ready for further analysis and prevents any noise from affecting the results.

### 3. Document-Term Matrix

To gain insights into the most common words used in each episode, we created a document-term matrix. This matrix represents the frequency of words across the episodes and allows us to analyze the patterns and identify significant terms.

### 4. Exploratory Analysis

In this step, we conducted exploratory analysis on the data. We generated word clouds and various graphs to visualize the most common words and their distribution in each episode. These visualizations provide a deeper understanding of the content and help identify key themes and sentiments.

### 5. Profanity Analysis

We analyzed the amount of profanity present in the transcripts. By using specific techniques or libraries, we calculated the frequency of profane words or phrases. This analysis gives insights into the language usage and intensity of emotions expressed in the series.

### 6. Sentiment Analysis of Routines

To analyze the sentiment of routines, we used sentiment analysis techniques to classify the overall emotional tone of each episode. By examining positive, negative, and neutral sentiments, we can understand the overall mood and emotional journey of the characters throughout the series.

### 7. Topic Modeling and Text Generation

In this step, we performed topic modeling on the transcripts. By applying techniques like Latent Dirichlet Allocation (LDA), we identified the underlying topics discussed in Money Heist. Additionally, we built a Markov chain function to generate text based on the learned patterns, allowing us to simulate character dialogues or create new scenes.

## Conclusion

This project provides a comprehensive analysis of the web series Money Heist through sentiment analysis, profanity analysis, and topic modeling. By leveraging web scraping, data cleaning, and various analytical techniques, we gain insights into the emotional aspects, language usage, and underlying themes of the series. The findings contribute to a deeper understanding and appreciation of the show.
