# NLP-LSA: Natural Language Processing with Latent Semantic Analysis

NLP-LSA is a Python project focused on applying Latent Semantic Analysis (LSA) to text data using scikit-learn. LSA is a powerful technique in natural language processing for uncovering latent semantic structures within large datasets. In this project, we apply LSA to a subset of the 20 newsgroups dataset to explore semantic relationships between documents.

## Introduction

Latent Semantic Analysis (LSA) is a mathematical and statistical method commonly used in natural language processing and information retrieval. It involves applying Singular Value Decomposition (SVD) to large datasets represented in matrix form, with the aim of extracting latent semantic structures within the data. This project demonstrates the application of LSA to text data using scikit-learn.

## Dataset

The fetch_20newsgroups dataset from scikit-learn's datasets module is utilized for this project. This dataset consists of approximately 20,000 newsgroup documents spanning 20 different categories or newsgroups. We focus on a subset of 5 newsgroups for simplicity and efficiency: 'alt.atheism', 'soc.religion.christian', 'comp.graphics', 'sci.electronics', and 'sci.space'.

## Implementation

The project implements LSA using scikit-learn's modules and functionalities. Key steps include:

- Fetching the 20 newsgroups dataset using `fetch_20newsgroups()` function.
- Vectorizing the text data using `CountVectorizer`.
- Performing Singular Value Decomposition (SVD) on the document-term matrix.
- Extracting latent semantic structures from the SVD results.

## Getting Started

To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/nlp-lsa.git
cd nlp-lsa
pip install -r requirements.txt
```
Then, run the main script to perform LSA on the dataset:

```bash
python main.py
```
