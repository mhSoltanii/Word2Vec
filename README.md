# Word2Vec – Traditional Model for Word Embedding

This project implements the **traditional Word2Vec model** (CBOW / Skip-gram) for learning vector representations of words from text data.  
It uses the Gensim library for training and supports preprocessing, training, and visualization of embeddings.

## Features
- Text preprocessing (tokenization, cleaning, removing URLs and non-alphabetic characters)
- Support for **Skip-gram** and **CBOW** architectures
- Adjustable parameters: `vector_size`, `window`, `min_count`, `epochs`
- Vocabulary inspection and similarity checks
- Dimensionality reduction (PCA) for visualization

## Requirements
- Python 3.8+
- Gensim
- NumPy
- scikit-learn
- Matplotlib

Install dependencies:
```bash
pip install gensim numpy scikit-learn matplotlib

