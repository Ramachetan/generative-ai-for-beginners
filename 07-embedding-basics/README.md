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
  - Vectors are typically 50 to 300 dimensions, which helps manage high-dimensional data effectively. But the recent innovations like GPT and BERT have embeddings with thousands of dimensions.

- **Usage**:
  - Use embeddings to measure similarities between inputs by calculating distances (e.g., cosine similarity) between vectors.

### What is Cosine Similarity?

- **Definition**:
  - Cosine similarity measures the cosine of the angle between two vectors, indicating how similar they are in direction.

- **Range**:
    - The similarity score ranges from -1 (completely opposite) to 1 (identical), with 0 indicating no similarity.

- **Formula**:
    - For vectors `A` and `B`, cosine similarity is calculated as: `cosine(A, B) = (A . B) / (||A|| * ||B||)`, where `A . B` is the dot product of `A` and `B`, and `||A||` is the magnitude of `A`.

- **Applications**:
    - Cosine similarity is widely used in recommendation systems, search engines, and clustering algorithms to measure similarity between items or documents.

### Use Cases

1. **Semantic Search**:
   - Text embeddings represent both the user's query and documents in a vector space. Documents closer to the query vector are ranked higher in search results.

2. **Text Classification**:
   - Train a model to map text embeddings to correct category labels (e.g., cat vs. dog, spam vs. not spam). Once trained, the model classifies new text inputs based on their embeddings.

3. **Recommendation Systems**:
    - Use embeddings to represent users, items, and interactions in a unified vector space. Recommend items similar to those interacted with by the user.

4. **Anomaly Detection**:
    - Detect outliers in high-dimensional data by measuring the distance between embeddings of normal and anomalous data points.


