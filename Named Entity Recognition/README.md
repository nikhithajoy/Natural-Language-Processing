# Named Entity Recognition (NER) with spaCy

This repository contains Python code demonstrating Named Entity Recognition (NER) using the spaCy library with the **en_core_web_sm** model, NER involves identifying entities like names, organizations, locations, etc., within text.

## What is Named Entity Recognition (NER)?
Named Entity Recognition (NER) is a natural language processing (NLP) task that aims to locate and classify named entities mentioned in unstructured text into pre-defined categories such as names of persons, organizations, locations, dates, etc. This facilitates information extraction and understanding from textual data.

## Implementation Details
The provided Python script showcases the following steps to perform NER using spaCy:

1. Loading the spaCy Model: Utilizes the en_core_web_sm model from spaCy for English language processing.
2. Processing Text Documents: Processes input text using spaCy's NLP pipeline to identify named entities.
3. Extracting Named Entities: Iterates through the extracted named entities (doc.ents) to access their text, label, and label explanation.
4. Visualization with displaCy: Utilizes spaCy's displacy module to visualize the identified named entities within the text.
