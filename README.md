# Sentiment-Analysis

This is a simple sentiment analysis script that uses a lexicon-based approach to determine the sentiment of a piece of text, such as a sentence or a paragraph. The script classifies the text into positive, negative, or neutral sentiments based on the presence of positive and negative words in the text.

## Table of Contents
- #Introduction
- #Approach
- #Data
- #Conclusion

## Introduction
Sentiment analysis is a natural language processing (NLP) technique that aims to determine the sentiment or emotional tone behind a piece of text. In this project, we use a lexicon-based approach with pre-defined lists of positive and negative words to classify the sentiment of sentences or paragraphs.

## Approach
The sentiment analysis is performed using a simple lexicon-based approach as follows:
1. Load two CSV files containing lists of positive and negative words.
2. Define a function `sentiment1(text)` to classify the sentiment of a single sentence using the lexicon approach.
3. Define another function `sentiment(text)` to classify the sentiment of a whole paragraph by applying the lexicon approach to each sentence.
4. The script assigns a sentiment score of 1 for positive, -1 for negative, and 0 for neutral sentiments based on the presence of positive and negative words in the text.

## Data
The script requires two CSV files containing lists of positive and negative words. The positive words are stored in words_positive.csv, and the negative words are stored in words_negative.csv
Additionally, the script reads text data from a CSV file named reviews.csv, which contains the reviews to be analyzed.

 ## Conclusion
 Thankyou for visiting my repo
