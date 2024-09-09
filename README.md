# Embedding-Model-
Embedding-Based Retrieval-Augmented Generation (RAG) System for Website Content
Description: This project develops a Retrieval-Augmented Generation (RAG) system that utilizes embeddings to enhance the relevance of content retrieval from website data. Using the avsolatorio/GIST-small-Embedding-v0 model, the system parses and embeds textual content from websites, which is stored in a CSV file. When a user inputs a query, the system computes an embedding for the question and compares it with the pre-computed website content embeddings. The comparison is performed using cosine similarity, allowing the system to identify and retrieve the most relevant content from the website.

The core functionality of the system includes:

Website Content Parsing: Extracting text data from a website and storing it in a CSV file for embedding generation.

Embedding Generation: Utilizing a local embedding model to compute embeddings for both the website content and user queries.

Similarity Matching: Using cosine similarity to compare the query embedding with the website content embeddings.

Content Retrieval: Retrieving and displaying the most relevant content based on similarity scores to answer the user's query.

This project enables accurate and efficient information retrieval from large-scale website data and provides an essential foundation for building robust question-answering systems using local models.
