# PlayingWIthNLP-Chatbot

This university project explores the **Cornell Movie-Dialogs Corpus** from Kaggle, using it to experiment with different Natural Language Processing techniques on movie dialogues.

The project includes data exploration, semantic embeddings, sentiment analysis, multilabel genre classification and a small chatbot based on dialogue generation.

## Project Overview

We started by cleaning and organizing the dataset, which contains movie lines, conversations, characters and movie metadata such as genres and IMDb ratings.

After the initial exploration, we worked on several NLP tasks:

- **Data exploration**: analysis of conversations, characters, movie genres and vocabulary growth.
- **Sentiment analysis**: estimation of positive and negative sentiment in dialogues using a pre-trained Transformer model.
- **Semantic search**: creation of text embeddings with `sentence-transformers` and comparison between movies using cosine similarity.
- **Genre classification**: multilabel classification of movie genres using both vocabulary-based models and a BERT-based approach.
- **Dialogue generation**: experiments with GPT-style models to generate movie-like conversations.

## Chatbot

The final part of the project is a small chatbot that combines some of the techniques developed in the notebook.

The chatbot is designed to:

- ask the user for a movie title;
- find the closest matching movie using semantic similarity;
- retrieve relevant dialogue context;
- generate a new dialogue-style response.
