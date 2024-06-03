# Vaccination Tweets NLP Analysis

## Overview

### This project involves Natural Language Processing (NLP) analysis of tweets related to vaccination. The goal is to preprocess, analyze, visualize, and model the textual data to gain insights into public sentiment and common themes around vaccination.

## Installation

### To get started, clone the repository and install the required libraries:

## Libraries Used

### pandas
### re
### seaborn
### matplotlib
### wordcloud
### textblob
### nltk
### plotly
### warnings
### logging
### scipy
### gensim
### pickle
### random
### sklearn

## Data Preprocessing

## The data preprocessing steps involve:

### Loading the data.
### Dropping unnecessary columns.
### Cleaning the text by removing URLs, special characters, and stop words.
### Tokenizing the text.

## Exploratory Data Analysis (EDA)

## Word Cloud
### Generated a word cloud to visualize the most frequent words in the tweets.

## Document-Term Matrix
### Created a document-term matrix to identify the most common words and their frequencies.
### Cleared newly added stop words and generated a new word cloud.

## Frequency Analysis
### Plotted the top 30 words in the tweets.

## Time Series Analysis

### Analyzed the number of tweets per day and visualized trends over time.
### Highlighted significant events such as the J&J vaccine authorization.

## Sentiment Analysis

## Polarity and Subjectivity
### Calculated the polarity and subjectivity of each tweet using TextBlob.

## Sentiment Classification
### Classified tweets into Positive, Negative, and Neutral categories.
### Visualized the distribution of sentiments.

## Sentiment Over Time
### Analyzed the distribution of sentiments over time and visualized it using line plots.

## Topic Modeling

## LDA Topic Modeling
### Applied Latent Dirichlet Allocation (LDA) to identify topics within the tweets.
### Attempted topic modeling using all text, only nouns, and nouns with adjectives.

## Text Generation

## Markov Chain Text Generation
### Built a Markov chain to generate text based on the corpus of tweets.

## Usage

### Data Preprocessing: Preprocess the data by running the data cleaning and tokenization steps.
### EDA: Visualize word clouds and plot frequency analysis charts.
### Time Series Analysis: Analyze and visualize the trends of tweets over time.
### Sentiment Analysis: Calculate polarity, classify sentiments, and visualize the results.
### Topic Modeling: Run LDA to extract topics from the tweets.
### Text Generation: Generate new text using the Markov chain model.

## Results

### The analysis provides insights into:

### Common themes and words used in vaccination-related tweets.
### Public sentiment towards vaccination.
### Temporal trends in tweet volume and sentiment.
### Key topics discussed in the tweets.

## Contributing

### Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License

### This project is licensed under the MIT License.
