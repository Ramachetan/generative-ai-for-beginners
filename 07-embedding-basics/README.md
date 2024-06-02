## Embeddings

Embeddings are numerical representations of complex data such as words, sentences, or even images and videos, in a continuous vector space. They help machine learning models to process and understand data more efficiently.

### Types of Embeddings

1. **Word Embeddings**:
   - **Examples**: Word2Vec, GloVe, FastText
   - Convert words into vectors so that words with similar meanings are closer in the embedding space.

2. **Sentence and Document Embeddings**:
   - **Examples**: BERT, Doc2Vec
   - Represent entire sentences or documents as vectors, capturing context and meaning beyond individual words.

3. **Text Embeddings**:
   - Similar to word embeddings, but focus on capturing the essence of larger text units like phrases or entire documents.

4. **Graph Embeddings**:
   - Represent nodes, edges, or entire graphs in a vector space, useful in network analysis or recommendation systems.

5. **Image Embeddings**:
   - **Examples**: CNNs
   - Used in tasks like image recognition and classification by representing images as vectors.

### How Embeddings Work

- **Training**:
  - Embeddings are learned by training a model on a specific task, like reconstructing linguistic contexts of words.

- **Dimensionality**:
  - Vectors are typically 50 to 300 dimensions, which helps manage high-dimensional data effectively.

- **Usage**:
  - Use embeddings to measure similarities between inputs by calculating distances (e.g., cosine similarity) between vectors.

### Use Cases

1. **Semantic Search**:
   - Text embeddings represent both the user's query and documents in a vector space. Documents closer to the query vector are ranked higher in search results.

2. **Text Classification**:
   - Train a model to map text embeddings to correct category labels (e.g., cat vs. dog, spam vs. not spam). Once trained, the model classifies new text inputs based on their embeddings.
