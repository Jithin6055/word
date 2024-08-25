Document Similarity and Topic Modeling with LDA and Word2Vec
This project analyzes a collection of documents to uncover hidden topics using Latent Dirichlet Allocation (LDA) and generates semantic word embeddings using Word2Vec to measure document similarity. The goal is to cluster documents based on their similarity and visualize the results using t-SNE.

Project Overview
Data Collection: We use the 20 Newsgroups dataset, which includes documents on diverse topics such as politics, sports, technology, and health.
Text Preprocessing: The text is preprocessed by tokenizing, lowercasing, and removing stopwords.
Topic Modeling (LDA): LDA is applied to uncover hidden topics in the documents.
Word Embeddings (Word2Vec): Word2Vec is used to create semantic embeddings for the documents.
Document Similarity: We calculate document similarity using LDA topic distributions and Word2Vec embeddings and visualize clusters using t-SNE.
Analysis: The effectiveness of LDA and Word2Vec in topic modeling, document similarity, and clustering is compared.
Prerequisites
Before you start, ensure you have the following installed:

Python 3.x
Jupyter Notebook or Google Colab
Required Python libraries:
gensim
nltk
scikit-learn
matplotlib
pyLDAvis