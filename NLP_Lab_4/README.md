# NLP Language Models with PyTorch

## Overview

This repository contains the implementation of various NLP tasks using PyTorch. The work is divided into three main parts: Classification Regression, Text Generation with Transformers, and Fine-tuning BERT for text classification.

#### Part 1: Classification Regression

1. **Data Collection**: Collect Arabic text data using BeautifulSoup on a specific topic (AI), and created a dataset where each text is assigned a relevance score between 0 and 10.

2. **Preprocessing Pipeline**: Performed text tokenization to split the text into individual tokens, Applied stemming to reduce words to their base or root form and Removed stop words to eliminate common words that do not contribute to the model's performance.

3. **Model Training**: Trained four different models: RNN, Bidirectional RNN, GRU, and LSTM. with Tuning hyperparameters such as learning rate, batch size, number of layers, and hidden units to optimize model performance.

4. **Model Evaluation**: Evaluated models using 'MSE'.

#### Part 2: Transformer (Text Generation)

1. **Model Setup**: Loaded the pre-trained GPT-2 model.

2. **Fine-Tuning**: Fine-tuned the GPT-2 model on a custom dataset (tmdb movies) to adapt it to specific text generation tasks.

3. **Text Generation**: Generated new paragraphs based on given sentences to test the fine-tuned model's text generation capabilities.

#### Part 3: BERT

1. **Data Preparation**: Prepared and preprocessed the Amazon review dataset to be compatible with BERT input requirements.

2. **Model Adaptation**:  Adapted the BERT embedding layer to the dataset and fine-tuned the pre-trained BERT model.

3. **Training and Hyperparameter Tuning**:  Fine-tuned the BERT model with various hyperparameters to achieve optimal performance.

4. **Model Evaluation**: Evaluated the model using standard metrics (accuracy, loss, F1 score) .

   
## Requirements
- PyTorch
- PyTorch-Transformers
- Transformers
- BeautifulSoup
- Additional libraries: pandas, numpy, sklearn, nltk
