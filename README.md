# Dream Analysis API with Flask and NLTK

## Overview

The Dream Analysis API is designed to analyze and retrieve dream objects based on user input using Natural Language Processing (NLP) techniques. The API preprocesses text data, tokenizes, removes stopwords, stems words, and calculates cosine similarity to find related dream objects.

## Features

- Preprocess and tokenize text using NLTK (Natural Language Toolkit).
- Calculate cosine similarity between user input and dream text.
- Retrieve related dream objects based on user input.
- Pagination routes to retrieve paginated dream objects.

## Requirements

- Python 3.x
- Flask
- Flask-CORS
- NLTK
- scikit-learn

## Setup and Installation

1. Clone the repository or download the code.
2. Install the required Python packages using pip:
   ```bash
   pip install flask flask-cors nltk scikit-learn


