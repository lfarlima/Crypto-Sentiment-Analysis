# Crypto Sentiments
## Sentiment analysis, Natural Language Processing, Word Clouds, Frequency Analysis, NGrams, Named Entity Recognition

### 1. Sentiment Analysis
Use the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions: 

Q: Which coin had the highest mean positive score?

A: *Ethereum had the highest mean positive score (0.0747).*

Q: Which coin had the highest compound score?

A: *The highest compound score is tied for Ethereum and Bitcoin (0.8316). *

Q. Which coin had the highest positive score?

A: *Both Bitcoin and Ethereum's highest positive score is 0.246.*


### 2. Natural Language Processing
**Tokenizer**
In this section, you will use NLTK and Python to tokenize the text for each coin. Be sure to: 
    1. Lowercase each word. 
    2. Remove Punctuation. 
    3. Remove Stopwords.

**NGrams and Frequency Analysis**
In this section you will look at the ngrams and word frequency for each coin.
    Use NLTK to produce the n-grams for N = 2.
    List the top 10 words for each coin.
    
**Word Clouds**
In this section, you will generate word clouds for each coin to summarize the news for each coin

### 3. Named Entity Recognition

In this section, you will build a named entity recognition model for both Bitcoin and Ethereum, then visualize the tags using SpaCy.
