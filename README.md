# Data-Science-Capstone-Assignment-2

# Project Overview
This project focuses on analyzing tweets related to "employee attrition risk, HR, or workplace" using Large Language Models (LLMs). It aims to understand the sentiment of these tweets and identify key topics of discussion. The results can offer insights into employee feelings and trends in the workplace, and the approach can be adapted to other business or HR-related issues.

# Components
Data Collection: Tweets related to employee attrition, HR, and workplace topics are fetched using Twitter API v2.
Sentiment Analysis: A machine learning model classifies each tweet as positive, negative, or neutral.
Topic Generation: An LLM identifies common topics from the tweets.
Visualization: Graphs and charts show the overall sentiment, top discussion topics, and tweet frequency over time.

# Dataset
The dataset is made up of recent tweets using the search query: "attrition risk of employee OR HR OR workplace lang
." Each tweet includes:

Timestamp: The time the tweet was posted.
Author_ID: A unique identifier for the author.
Tweet Content: The actual text of the tweet.

# Data Processing
Cleaning Tweets: Removes unwanted characters, links, and unnecessary words from tweets.
Sentiment Analysis: Each cleaned tweet is analyzed and classified into a sentiment category (positive, negative, or neutral). A Random Forest algorithm is used for validation and classification.

# Topic Generation: Uses an LLM to identify key topics discussed in each tweet.
Model
Sentiment Analysis Model: We use a pre-trained model, such as GPT-2, to classify the sentiment of tweets.
Topic Generation Model: A text generation LLM extracts the main topics from tweets, offering insights into common themes like "job satisfaction" or "HR policies."

# Deployment
The model is deployed using Flask to allow easy interaction and visualization of results.

# Results
Sentiment Distribution: Displays the proportion of tweets that are positive, negative, or neutral about employee attrition and workplace issues.

# Top Topics: Shows the most commonly discussed themes, such as "toxic work environment" or "job security."
Tweet Frequency: Tracks when discussions on these topics are most active, highlighting peak times for engagement.
This simplified approach provides actionable insights into employee sentiment and workplace-related discussions on Twitter.
