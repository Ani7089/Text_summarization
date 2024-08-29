# Text Summarization Project

## Overview

This project focuses on developing an text summarization model using the Inshorts news dataset. The primary goal is to create a system that can generate concise summaries of longer text articles, maintaining key information while reducing content length.

## Features

- **Text Preprocessing**: Clean and preprocess raw text data from the Inshorts dataset.
- **Sentence Embedding**: Transform sentences into vector representations using various techniques such as TF-IDF, word embeddings, or sentence transformers.
- **Text Summarization**: Implement extractive summarization methods including but not limited to:
  - Frequency-based summarization
  - Graph-based summarization (e.g., TextRank)
  - Clustering-based summarization

## Dataset

### Inshorts Dataset

- **Source**: The Inshorts dataset consists of short news articles from the Inshorts platform, which provides summaries of news articles in 60 words or less.
- **Format**: The dataset is typically structured as JSON files, where each entry includes:
  - `headline`: The headline of the article.
  - `short_description`: A brief summary of the article.
  - `date`: The publication date.
  - `category`: The category of the news article.
  - `link`: The original article link.
  
- **Usage**: In this project, the dataset is used to train and test the text summarization model. The dataset is split into training, validation, and testing sets for model evaluation.

## Installation

### Prerequisites

- Python 3.x
- Required Python libraries (listed in `requirements.txt`):
  - NumPy
  - Pandas
  - Scikit-learn
  - NLTK
  - Gensim
  
### Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Text_summarization.git

2. Navigate to the project directory:
   ```bash
	cd Text_summarization
3. Install the required libraries:
	``bash
	pip install -r requirements.txt
4. Download the Inshorts dataset and place it in the data directory.


### Results

- The model's performance is evaluated using the ROUGE metric.
- You can find the evaluation results and sample summaries in the results directory.

### Future Work

- Implementing abstractive summarization techniques.
- Fine-tuning the model with larger and more diverse datasets.
- Enhancing the user interface for better user experience.











