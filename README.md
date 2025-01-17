# Technology-News-Insight-Engine

## Project Overview:
The Technology News Insights Engine analyzes various technology news articles to uncover trends in tech products and services for advising tech startups on how to grow their businesses.

## [Engine Sturcture and results](https://github.com/JunJul/Technology-News-Insight-Engine/blob/Master/BTT_AccentureTeam1B.pptx.pdf)
- All results will be on our team's slides.
- My main responbility in this project is to clean, organize Tech News data and create a recommendation sysytem.

## [Technology News Insight Engine](https://github.com/JunJul/Technology-News-Insight-Engine/blob/Master/Tech_News_Insight_Engine.ipynb)
- An object groups the functionality of data cleaning and News Categorization.
- The Engine uitilizes berTopic and Groq API to categorize Tech News articles and filter out non-Tech News articles

## [Data Cleaning Results](https://github.com/JunJul/Technology-News-Insight-Engine/blob/Master/Number_of_Tokens.ipynb)
- Shows distribution in number of words before cleaning and after cleaning.

## [Recommendation System](https://github.com/JunJul/Technology-News-Insight-Engine/blob/Master/Recommendation_System.ipynb)
- Retrieveal Arguemented Generation based on Llama-2-7b-chat-hf
- Retrieve and Re-rank from sentence transformer
- sentiment analysis

## [Engine tools](https://github.com/JunJul/Technology-News-Insight-Engine/blob/Master/Technology_News_Insight_Engine_Tools.ipynb)
- contains all objects used by Technology News Insight Engine such as data cleaning, summarization and Groq.
- Data Cleaning: remove stopwords, lemmatize words, and tokenize sentences.
- Summarization: summarize a long News article by frequency of word based and textRank summarization.
- Groq: is a AI Cloud platform where I can use Llamma3 to categorize News articles

## Notes
The Technology News Insight Engine is designed to serve as a demo that empowers technology consultants to quickly access and analyze information requested by their clients. By streamlining the process of extracting trends and insights from technology news articles, the engine helps consultants make informed decisions, identify opportunities, and provide strategic recommendations with efficiency and precision.
