# Text Similarity with Cosine Similarity Calculation

This Python script calculates the cosine similarity between two text documents based on their TF-IDF (Term Frequency-Inverse Document Frequency) representations. The cosine similarity metric measures the similarity between two vectors in a vector space and is commonly used in text analysis and information retrieval.

## Overview
The program preprocesses the input text documents by tokenization, lowercase conversion, and stop word removal using NLTK (Natural Language Toolkit). It then converts the preprocessed text into TF-IDF vectors using scikit-learn (sklearn) and computes the cosine similarity between these vectors to determine the textual similarity between the documents.

## Cosine Similarity:

Cosine similarity is a measure of similarity between two non-zero vectors in a vector space. It calculates the cosine of the angle between the vectors, which reflects how closely the vectors are aligned.
The cosine similarity value ranges from -1 (completely opposite) to 1 (exactly the same), with 0 indicating orthogonality (no similarity).

## Interpretation:

A cosine similarity score of 0.0 between text1 and text2 means that the angle between their TF-IDF vectors is 90 degrees (orthogonal).
In terms of textual similarity, a cosine similarity score of 0.0 suggests that the two text documents are dissimilar or unrelated based on the words and their frequencies in the 
