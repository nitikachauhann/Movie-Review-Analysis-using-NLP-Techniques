
# IMDB Movie Reviews

## Overview
This project demonstrates a Natural Language Processing (NLP) pipeline using the IMDB Movie Reviews dataset. The project covers multiple NLP stages including preprocessing, morphological analysis, lexical analysis, syntax analysis, semantic analysis, discourse analysis, feature extraction, and word embeddings.

The main objective of this project is to analyze movie reviews and understand how different NLP techniques process textual data step-by-step.

---

## Features

- Data loading using Pandas
- Text preprocessing and cleaning
- Tokenization
- Stopword removal
- Stemming
- Lemmatization
- TF-IDF feature extraction
- POS (Parts-of-Speech) tagging
- Named Entity Recognition (NER)
- Context-Free Grammar (CFG) parsing
- Dependency parsing
- Semantic analysis using WordNet
- Word Sense Disambiguation
- Word Embeddings using Word2Vec
- Discourse analysis

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NLTK
- spaCy
- Scikit-learn
- Gensim

---

## Dataset

Dataset Used:
- IMDB Movie Reviews Dataset

The dataset contains movie reviews labeled as:
- Positive
- Negative

---

## Project Workflow

### 1. Data Loading
- Mount Google Drive
- Load IMDB dataset using Pandas

### 2. Preprocessing
- Remove HTML tags
- Remove special characters
- Convert text to lowercase
- Tokenization
- Stopword removal

### 3. Morphological Analysis
- Stemming
- Lemmatization

### 4. Feature Extraction
- TF-IDF Vectorization

### 5. Lexical Analysis
- POS Tagging
- Named Entity Recognition

### 6. Syntax Analysis
- Context-Free Grammar Parsing
- Dependency Parsing

### 7. Semantic Analysis
- Synonym extraction
- Word meaning identification
- Word Sense Disambiguation

### 8. Word Embeddings
- Word2Vec implementation
- Similar word detection

### 9. Discourse Analysis
- Sentence tokenization
- Coherence checking

---

## Installation

Install required libraries:

```bash
pip install pandas nltk scikit-learn spacy gensim
````

Download spaCy model:

```bash
python -m spacy download en_core_web_sm
```

---

## Running the Project

Open the notebook in Google Colab or Jupyter Notebook and execute the cells sequentially.

---

## Output Examples

* Cleaned movie reviews
* Tokenized words
* Stemmed and lemmatized tokens
* TF-IDF feature vectors
* POS tags
* Named entities
* Parse trees
* Semantic meanings
* Word embeddings

---

## Learning Outcomes

This project helps in understanding:

* Core NLP pipeline stages
* Text preprocessing techniques
* Language structure analysis
* Semantic interpretation
* Machine understanding of textual data

---

## Future Enhancements

* Add sentiment classification model
* Use Transformer-based embeddings like BERT
* Add visualization dashboards
* Deploy as a web application

---

## Author

Nitika
