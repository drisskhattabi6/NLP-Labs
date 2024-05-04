
# NLP Lab 2: Rule-Based NLP and Word Embedding

## Objective
The main purpose of this lab is to gain familiarity with rule-based NLP using regular expressions (regex) and various word embedding techniques in natural language processing (NLP).

## Part 1: Rule-Based NLP and Regex
### Task:
Using regular expressions, generate a bill from a given text description of purchased items.

### Approach:
- Define regex patterns to extract product names, quantities, and prices from the text.
- Iterate through matches and calculate the total price for each item.
- Display the generated bill in a tabular format.

### Example Output:
```
Generated Bill:
| Product             | Quantity | Unit Price | Total Price |
|---------------------|----------|------------|-------------|
| Samsung smartphone  | 3        | 150        | 450         |
| Banana              | 4        | 1.2        | 4.8         |
| Hamburger           | 1        | 4.5        | 4.5         |
```

## Part 2: Word Embedding
### Task:
Apply various word embedding techniques including one hot encoding, bag of words, TF-IDF, Word2Vec (Skip-gram, CBOW), GloVe, and FastText on a dataset.

### Approach:
- Implement each technique and analyze the resulting vectors.
- Visualize the encoded vectors using the t-SNE algorithm for comparison.
- Evaluate the effectiveness of each technique based on semantic similarity and performance in downstream NLP tasks.

### Conclusion:
- Each word embedding technique has its own strengths and weaknesses.
- Word2Vec, GloVe, and FastText are popular choices for capturing semantic relationships in text data.
- The choice of technique depends on the specific requirements of the task and the characteristics of the dataset.
