# LLM-Project
Custom Search Engine Using Fine-Tuned LLMs

## Objective:
A custom search engine that takes a query and returns the most relevant results from a corpus of documents. The system involve:
- Embeddings for document representation
- Fine-tuning a transformer model for better understanding of domain-specific queries
- Leveraging Chatgpt for summarizing or answering questions based on search results
- Efficient search using vector search

## Methodology:
1. Word Embeddings
  - Preparing a corpus of text documents (this can be anything from a set of research papers to articles).
  - Used **Word2Vec** embeddings to convert each document into a vector representation.
2. Search Functionality (Custom Search with Embeddings)
  - Built a custom search function using **cosine similarity** to match query vectors with document vectors
  - Created a function that converts a query into a vector and **ranks documents based on their similarity** to the query.
3. Fine-Tuning with Transformers - using **Huggingface Transformers**

## Technologies Used
- Google Colab
