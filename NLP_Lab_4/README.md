# NLP Language Models with PyTorch

## Overview

This repository contains the implementation of various NLP tasks using PyTorch. The work is divided into three main parts: Classification Regression, Text Generation with Transformers, and Fine-tuning BERT for text classification.

## Part 1: Classification Regression

### Data Collection
- Scraped Arabic text data on a specific topic using Scrapy and BeautifulSoup.
- Assigned relevance scores (0-10) to each text.

### Preprocessing Pipeline
- Tokenization, stemming, lemmatization, and stop word removal.
- Score discretization if necessary.

### Models
- Implemented and trained RNN, Bidirectional RNN, GRU, and LSTM models.
- Tuned hyperparameters for optimal performance.

### Evaluation
- Used accuracy, precision, recall, F1 score, and BLEU score to evaluate model performance.

## Part 2: Transformer (Text Generation)

### Model Setup
- Installed PyTorch-Transformers and loaded the pre-trained GPT-2 model.

### Fine-Tuning
- Fine-tuned GPT-2 on a custom dataset.

### Text Generation
- Generated new paragraphs from given sentences to test the model.

## Part 3: BERT

### Data Preparation
- Used the Amazon review dataset and prepared it for BERT.

### Model Adaptation
- Adapted and fine-tuned the BERT embedding layer.

### Training and Hyperparameter Tuning
- Fine-tuned the BERT model with various hyperparameters.

### Evaluation
- Evaluated using accuracy, loss, F1 score, BLEU score, and BERT score.

## Conclusion
- Provided insights into the performance and applicability of pre-trained BERT models for text classification and regression tasks.

## Requirements
- PyTorch
- PyTorch-Transformers
- Transformers
- BeautifulSoup
- Additional libraries: pandas, numpy, sklearn, nltk