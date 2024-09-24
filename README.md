# NLP Text Summarization Project

## Overview

This project is an implementation of basic Natural Language Processing (NLP) techniques to summarize a given piece of text. The project leverages the nltk library for various NLP tasks, such as tokenization, stemming, and stopword removal. The primary goal is to produce a summary of a larger body of text by identifying key sentences and filtering out less important words.

## Features

• Sentence Tokenization: Breaking the text into sentences using nltk.sent_tokenize.<br>
• Word Stemming: Reducing words to their base form using PorterStemmer.<br>
• Stopwords Removal: Filtering out common words that do not carry significant meaning using nltk.corpus.stopwords.<br>
• Summarization: Generating a summary by identifying and extracting key sentences.<br>

## Requirements

• Python 3.x<br>
• Jupyter Notebook<br>
• Libraties - `nltk`<br>

## Installation

```bash
pip install nltk
```

```bash
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage 

• Load the notebook in Jupyter.<br>
• Follow the instructions to execute each cell.<br>
• The notebook processes a sample text about the decline of the Indian Rupee and generates a summary using basic NLP techniques.<br>

## Result 

The ongoing decline of the Indian Rupee (INR) against the US Dollar (USD) is a complex issue influenced by various economic and geopolitical factors...
