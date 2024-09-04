# Skip-Gram Model in Python

## Overview
This project implements a Skip-Gram model in Python, 
designed to capture and quantify the semantic relationships between words by analyzing their contextual proximity within a large corpus of text.
The focus of the implementation is on efficient memory management, runtime optimization, and overall model performance.

## Features
- **Find Most Similar**: Identify the most similar words to a given word using the trained model.
- **Dimensionality Reduction**: Visualize word embeddings in 3D space using PCA (Principal Component Analysis) to understand word relationships.
- **Clustering**: Apply K-means clustering to group words into `k` clusters based on their semantic similarity.

## Installation
To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/EdenBarda/Word2Vec.git
cd Word2Vec
pip install -r requirements.txt
