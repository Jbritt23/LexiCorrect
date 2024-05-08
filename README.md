# LexiCorrect

## Description
LexiCorrect is a Python-based spell-checking utility that utilizes the NLTK Brown Corpus to provide word suggestions for misspelled words in a text file. The application compares each word against a list of known words derived from the corpus, calculates the similarity based on several metrics, and suggests the most likely correct spelling for each unrecognized word.

## Features
- **NLTK Brown Corpus**: Leverages a comprehensive English corpus for a broad set of known words.
- **Custom Similarity Scoring**: Implements a custom algorithm to score similarities between words, accounting for exact matches, length similarities, and character swaps.
- **File Handling**: Processes input text files to identify misspelled words and outputs suggestions to a designated file.

## Installation

### Prerequisites
This application requires Python 3 and the installation of the NLTK library, which can be installed using pip:
```bash
pip install nltk
