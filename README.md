# Sentiment Analysis of YouTube Comments on US Election 2024

This project analyzes the sentiment of YouTube comments related to the US Election 2024, focusing on videos featuring the Democratic and Republican parties. By leveraging advanced natural language processing techniques and machine learning models, the project provides insights into public opinion on key political figures and parties.

## Table of Contents
- [Overview](#overview)
- [Data Collection](#data-collection)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project utilizes the YouTube Data API to scrape comments from videos related to the US Election 2024. The comments are analyzed to determine sentiment towards the Democratic and Republican parties, particularly focusing on videos related to Donald Trump and Joe Biden. The analysis involves preprocessing, sentiment labeling, and applying machine learning models to achieve meaningful insights.

## Data Collection
- **YouTube Data API**: Used to scrape comments from YouTube videos.
- **Target Videos**: Focused on videos discussing the Democratic and Republican parties.
- **Number of Comments**: Collected a total of 10,000 comments from videos featuring Donald Trump and Joe Biden.

## Preprocessing
- **NLTK and spaCy**: Utilized for preprocessing the text data, including tokenization, stopword removal, and lemmatization.
- **Named Entity Recognition (NER)**: Performed using spaCy to identify mentions of political figures within the comments.

## Modeling
- **Sentiment Labeling**: Used VADER sentiment analysis tool to label comments as positive, negative, or neutral.
- **Word Embeddings**: Trained Word2Vec embeddings to represent the comments in vector form.
- **BiLSTM and GRU Models**: Implemented and trained BiLSTM and GRU models for sentiment analysis, achieving an F1 score of 82%.
- **BERT Model**: Fine-tuned a BERT model from Hugging Face to analyze the sentiment of 10,000 comments, specifically focusing on Trump and Biden videos.

## Results
- **Sentiment Analysis**:
  - 45% of the comments were positive towards the Republican Party.
  - 35% of the comments were positive towards the Democratic Party.
- The analysis provides insights into public sentiment and political leanings based on YouTube comments during the 2024 election cycle.

