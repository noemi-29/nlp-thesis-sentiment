# nlp-thesis-sentiment

This repository contains the code for my thesis project, which combines Sentiment Analysis and Corpus-Assisted Critical Discourse Analysis (CACDA) on tweets about Game of Thrones.

📌 Project Overview:

Dataset: Tweets extracted from the Game of Thrones Twitter dataset on Kaggle (https://www.kaggle.com/datasets/monogenea/game-of-thrones-twitter), manually labeled for sentiment.

Approach:
- Sentiment Analysis: A Multi-Layer Perceptron (MLP) was trained on part of the labeled data and tested on the remainder. Tweet embeddings were generated using the cardiffnlp/twitter-roberta-base-sentiment model (https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment) before being fed into the MLP.
- Corpus-Assisted Critical Discourse Analysis (CACDA): The code replicates key functions of the linguistic software WordSmith to extract statistical data from the corpus.

This repository provides scripts for data preprocessing, model training, evaluation, and linguistic analysis.

