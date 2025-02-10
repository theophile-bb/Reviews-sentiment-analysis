# Reviews Sentiment Analysis
This project focuses on analyzing customer reviews using Transformers (RoBERTa). The goal was to determine the sentimentof the reviews—positive, negative, or neutral—using natural language processing (NLP) techniques and ML algorithms. 

## Dataset
This study was led on 33700 hotel reviews. Each entry is a different review that I wanted to analyze using a Transformer.

## Methodology
The analysis is structured as follows:

### Data Preprocessing:

Text Cleaning: Removing punctuation, numbers, and special characters.

Tokenization: Splitting text into individual words or tokens (with .

Stop Words Removal: Eliminating common words that do not contribute to sentiment.

Stemming/Lemmatization: Reducing words to their root forms.

### Tokenization and sentiment classification:

Use of pretrained RoBERTa for tokenization and to get the sentiment list.

### Feature Extraction and visualization:

Bag of Words (BoW): Representing text as a frequency distribution of words.

