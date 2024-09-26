# Web-Scraping-and-Customer-Review-Analysis

Introduction

This project aims to scrape reviews of British Airways from AirlineQuality.com, clean and preprocess the text data, and perform sentiment analysis and topic modeling to gain insights into customer opinions.

The following tools and libraries were used in this project:

Web Scraping:
requests library for sending HTTP requests and retrieving HTML content
BeautifulSoup library for parsing HTML content and extracting review text
Data Manipulation and Analysis:
pandas library for data manipulation and storage
numpy library for numerical computations
Natural Language Processing (NLP):
nltk library for tokenization, stopword removal, and lemmatization
TextBlob library for sentiment analysis
Topic Modeling:
sklearn library for CountVectorizer and Latent Dirichlet Allocation (LDA)
Visualization:
matplotlib library for plotting sentiment category distribution
wordcloud library for generating word cloud images
Project Steps

The project consists of the following steps:

Web Scraping: Scrape reviews from AirlineQuality.com using requests and BeautifulSoup.
Data Preprocessing: Clean and preprocess the review text data using nltk and re.
Sentiment Analysis: Perform sentiment analysis using TextBlob and classify reviews into positive, negative, and neutral categories.
Topic Modeling: Apply LDA to the preprocessed review text data using sklearn.
Visualization: Visualize the sentiment category distribution using matplotlib and generate a word cloud image using wordcloud.
Code Organization

The code is organized into the following sections:

Web scraping and data collection
Data preprocessing and cleaning
Sentiment analysis
Topic modeling
Visualization
Each section is clearly separated and commented to facilitate understanding and modification of the code.

Conclusion

This project demonstrates a comprehensive approach to analyzing customer reviews of British Airways. The results provide insights into customer opinions and sentiment, which can be used to improve customer service and overall airline experience.
