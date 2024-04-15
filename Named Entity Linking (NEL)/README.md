# Named Entity Linking (NEL) with spaCy and Wikidata API
This Python script performs Named Entity Linking (NEL) by leveraging spaCy for named entity recognition (NER) and querying the Wikidata API to retrieve entity details based on recognized named entities in text.

## Overview
The script uses the en_core_web_sm model from spaCy for NER to identify named entities (e.g., persons, organizations, locations) in the input text. For each recognized named entity, the script queries the Wikidata API to retrieve additional entity information such as description and Wikidata ID.

## NEL
NEL stands for Named Entity Linking, which is a natural language processing (NLP) task that involves identifying named entities (such as persons, organizations, locations) in text and linking them to unique entities or concepts in a knowledge base or database. The goal of Named Entity Linking is to disambiguate and resolve named entities to specific entities or entities with rich contextual information, enabling deeper semantic understanding and information retrieval.

The process of Named Entity Linking typically involves the following steps:

### Named Entity Recognition (NER):

* Identify and classify spans of text that correspond to named entities (e.g., person names, organization names, locations) within the input text.
* Example: In the sentence "Barack Obama was the 44th President of the United States," the named entities are "Barack Obama" (PERSON) and "United States" (GPE - geopolitical entity).

### Candidate Generation:

* Generate potential candidate entities (or entity mentions) for each recognized named entity based on its surface form (textual representation).
* Example: For the named entity "Barack Obama," potential candidates could include entries corresponding to Barack Obama in a knowledge base (e.g., Wikidata, DBpedia).

### Entity Disambiguation:

* Resolve the ambiguity of named entity mentions by selecting the correct entity from the candidate set.
* Utilize contextual information such as surrounding words, entity types, and relationships to disambiguate the named entity.
* Example: Disambiguating "Washington" to refer to "George Washington" (PERSON) vs. "Washington, D.C." (GPE) based on the context of the sentence.

### Entity Linking:

* Link each recognized named entity to a unique entity identifier (e.g., Wikidata ID, DBpedia URI) in a structured knowledge base or database.
* This linking process establishes connections between entities in text and entities in a knowledge graph or database, enabling richer semantic understanding and information retrieval.
