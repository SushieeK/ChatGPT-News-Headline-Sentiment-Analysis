# Chat GPT News Headline Sentiment Analysis Report
**Date**: 12 May 2023  
**Course**: Big Data, Professor Rodriguez  
**Semester**: Spring 2023  

## Introduction

In today’s digital world, news headlines play a vital role in shaping public opinion and influencing decision-making processes. The advent of artificial intelligence (AI) and natural language processing (NLP) technologies has revolutionized the way news is created, disseminated, and consumed. ChatGPT, a new “state-of-the-art” language model developed by OpenAI, represents a significant milestone in AI-driven language generation. Launched on November 30th, 2022, ChatGPT has attracted widespread attention and sparked intense discussions across various domains.
This final project aims to investigate the sentiment of news headlines related to ChatGPT and how that sentiment has evolved since ChatGPT’s launch. By analyzing the sentiment of these headlines, we can gain valuable insights into public perception and the overall attitude towards surrounding ChatGPT.


## Problem Statement

This project addresses the sentiment analysis of ChatGPT-related news headlines over time, crucial for understanding public sentiment and its implications for stakeholders. Utilizing the Python Google News API, GNews, we collected and analyzed articles from November 30, 2022, to April 30, 2023, using Kafka and Spark Structured Streaming for data processing.

### Objectives

- Analyze ChatGPT-related news headline sentiment.
- Track sentiment trends post-launch.
- Examine sentiment distribution across different publishers.
- Offer insights and analysis on public sentiment towards ChatGPT.

## Background Concepts

### Sentiment Analysis

Sentiment analysis evaluates the emotional tone of text, classifying it as positive, neutral, or negative. This technique provides valuable insights into the expressed opinions, emotions, and attitudes in text data through computational methods.

### Data Pipeline

Our project's data pipeline starts with GNews as the data source, using Kafka for data transportation to Spark, where sentiment analysis is performed. The pipeline integrates various tools, including TextBlob and NLTK, for effective sentiment analysis, with MongoDB, Kafka, and Parquet Files serving as output sinks for the processed data.

![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/04caeeac-1036-46e9-bcea-e604d52cf6e1)


### Big Data and Its Relevance

This project exemplifies a Big Data endeavor, utilizing advanced tools and methodologies to handle and analyze large datasets efficiently, showcasing the project's alignment with Big Data principles and practices.

## Tools and Technologies

- **Google Colaboratory**: For coding and collaboration.
- **GNews API**: To fetch relevant articles.
- **Apache Kafka & Spark**: For data ingestion and processing.
- **TextBlob & NLTK**: Libraries for sentiment analysis.
- **MongoDB**: For data storage and analysis.

## Analysis and Insights

### Data Visualization

Visualizations created using MongoDB Atlas reveal the sentiment distribution among ChatGPT-related articles, indicating a predominance of neutral sentiments, followed by positive and negative sentiments.

![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/164f7bb4-acfb-49cd-b233-889936d100f9)
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/29f9b1d2-f032-43b2-a699-3e1f8a47164d)
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/7b0748b1-9e2e-4334-a6a1-c73b1b0eb03b)
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/e1f14be2-b844-4d30-a791-2213a40d167a)
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/8cf5f959-83c9-435d-b3b7-2ff5b690ca28)



### Sentiment Trends

The analysis highlights stable sentiment ratios over time, despite an increase in article volume, particularly in March and April 2023. Notably, the initial weeks post-launch showed a higher positive sentiment, which stabilized over time.

![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/f94ce46e-40c8-4d59-acc6-3cbfe2ca2c56)


### Publisher Analysis

The most frequent publishers, including Fast Company and Forbes, showed varying sentiment distributions, with Fast Company exhibiting a notably positive sentiment.
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/36349bf4-e84f-4d0d-bbcc-c2f83b5b2bb0)
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/3ad34e11-6376-4d16-9a24-8db17832585f)
![image](https://github.com/SushieeK/ChatGPT-News-Headline-Sentiment-Analysis/assets/127150757/b896e02d-0750-456e-99b2-6f722f19aceb)

## Conclusion

Our findings indicate a predominantly neutral sentiment towards ChatGPT in news headlines, with a consistent sentiment distribution over time. This project underscores the capability of Big Data architectures to manage and analyze large datasets efficiently, providing valuable insights into public sentiment on contemporary issues.

## References

- Include references to all sources cited in your analysis, formatted appropriately.

Ali, M. (2023). NLTK Sentiment Analysis Tutorial for Beginners. https://www.datacamp.com/tutorial/text-analytics-beginners-nltk Apache Kafka. (n.d.). Apache Kafka. https://kafka.apache.org/intro
Cordon, T. (2022, March 30). Enabling streaming data with Spark Structured Streaming and Kafka. Medium. https://medium.com/data-arena/enabling-streaming-data-with-spark- structured-streaming-and-kafka-93ce91e5b435
Dominguez, H. R. (2022, May 14). Twitter sentiment analysis using Zookeeper, Kafka and PySpark live-streaming on Windows 10 in 2022. Medium. https://medium.com/mcd- unison/twitter-sentiment-analysis-using-zookeeper-kafka-and-pyspark-live-streaming-on- windows-10-in-2022-ada7757097a2
Gongang, L. (2022a, March 12). Apache Spark Structured Streaming - Lorena Gongang - Medium. Medium. https://medium.com/@lorenagongang/apache-spark-structured- streaming-69f06c490d8c
Gongang, L. (2022b, March 19). Sentiment analysis on streaming Twitter data using Kafka, Spark Structured Streaming & Python (Part 2). Medium. https://medium.com/@lorenagongang/sentiment-analysis-on-streaming-twitter-data- using-kafka-spark-structured-streaming-python-part-b27aecca697a
Gongang, L. (2022c, March 26). Sentiment analysis on streaming Twitter data using Kafka, Spark Structured Streaming & Python (Part 3). Medium. https://medium.com/@lorenagongang/sentiment-analysis-on-streaming-twitter-data- using-kafka-spark-structured-streaming-python-part-eaa9f0af076d



