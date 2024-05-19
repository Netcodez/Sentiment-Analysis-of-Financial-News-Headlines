# Sentiment Analysis of Financial News Headlines

## Project Overview

This project utilizes sentiment analysis to extract insights from financial news headlines with the goal of predicting market sentiment and making informed trading decisions. By analyzing headlines from trusted sources on [FINVIZ.com](https://finviz.com), we aim to better understand market emotions and potentially forecast stock performance.

![Facebook headlines from FINVIZ.com](https://assets.datacamp.com/production/project_611/img/fb_headlines.png)

## Introduction

Financial news plays a critical role in market dynamics. Sentiment analysis of these news headlines can provide valuable insights into market sentiment, helping traders and investors make informed decisions. This project aims to leverage sentiment analysis to extract emotions from financial news headlines and predict market trends.

## Setup

To begin, mount your Google Drive to access the dataset. Import the necessary libraries and download the VADER lexicon for sentiment analysis. 

## Data Collection

Load HTML files containing the news headlines from your Google Drive. These files will be parsed to extract the headlines for sentiment analysis.

## Data Exploration

Explore the structure of the data by reading a single day's headlines and examining the HTML tags that contain the relevant information. This helps in understanding how the data is organized and how it can be parsed effectively.

## Data Extraction

Extract the news headlines from the HTML files. The data is organized into a structured format, ready for sentiment analysis.

## Sentiment Analysis

Enhance the sentiment analysis with domain-specific words and their corresponding sentiments. This step involves updating the VADER lexicon to include words commonly used in financial news.

## Results Visualization

Visualize the sentiment analysis results with a bar chart. This helps in understanding the overall sentiment trends for different stocks over time.

## Data Cleaning

Identify and handle duplicate headlines and weekends. This step is crucial to ensure the accuracy and quality of the dataset, as duplicate headlines can skew the sentiment analysis results.

## Case Study: Single Trading Day Analysis

Focus on a single trading day and one stock to better understand the dataset. This involves examining the headlines and their sentiment scores in detail for a specific day.

## Visualizing the Single Day Sentiment

Plot the sentiment scores for a single trading day. This provides a detailed view of the positive, negative, and neutral sentiments for a specific stock on a particular day.

## Conclusion

By following this structured approach, we can analyze and visualize sentiment trends in financial news, potentially informing trading strategies and decisions. This project demonstrates how sentiment analysis can be applied to financial data, offering insights into market sentiment and aiding in the development of data-driven trading strategies.
