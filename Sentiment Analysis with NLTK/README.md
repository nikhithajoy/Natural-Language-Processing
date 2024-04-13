# Sentiment Analysis with NLTK

This Python program demonstrates sentiment analysis using NLTK (Natural Language Toolkit) library. It preprocesses input text, analyzes sentiment using NLTK's SentimentIntensityAnalyzer, and visualizes sentiment distribution.

## Prerequisites
Before running the program, ensure you have the following installed:

* Python 3.x
* NLTK (Natural Language Toolkit)
* Matplotlib (for plotting)

You can install NLTK and Matplotlib using pip:
~~~
pip install nltk matplotlib
~~~

Additionally, download the required NLTK resources (if not already downloaded) by uncommenting and running the following lines at least once:
~~~
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('vader_lexicon')
~~~

## Sentiment Analysis with NLTK's SentimentIntensityAnalyzer
The sentiment analysis is performed using NLTK's SentimentIntensityAnalyzer class, which is part of NLTK's nltk.sentiment module. This analyzer uses a lexicon-based approach to assign sentiment scores to text.
* Lexicon: NLTK's SentimentIntensityAnalyzer uses the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon, which contains words annotated with sentiment scores (positive, negative, or neutral).
* Sentiment Scores: The SentimentIntensityAnalyzer computes a sentiment score for a given text using four intensity metrics: positive, negative, neutral, and compound. The compound score is a normalized weighted composite score that ranges from -1 (most negative) to 1 (most positive).

For more details about NLTK's SentimentIntensityAnalyzer, refer to the [NLTK documentation](https://readthedocs.org/projects/nltk/downloads/pdf/latest/).
