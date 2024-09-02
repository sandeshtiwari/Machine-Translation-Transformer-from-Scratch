# Machine Translation Project: Transformers from Scratch

## Overview

This project implements a Machine Translation system using Transformers from scratch. The primary goal is to translate text between different languages by leveraging the powerful Transformer architecture, which has become a cornerstone in natural language processing.

## Features

- **Custom Transformer Model**: The project features a custom-built Transformer model that learns to translate text with a high degree of accuracy.
- **Language Support**: The project supports multiple languages, with pre-trained tokenizers for English, Spanish, and Italian.
- **Attention Visualization**: Tools are included to visualize the attention mechanism in the Transformer, providing insights into how the model processes input sentences.

## Project Structure

- `config.py`: Contains the model's hyperparameters and configurations for training.
- `dataset.py`: Manages data loading, preprocessing, and batching for both training and evaluation.
- `model.py`: Implements the Transformer architecture, including the encoder, decoder, and attention mechanisms.
- `train.py`: Script for training the Transformer model using the provided datasets.
- `inference.ipynb`: Jupyter notebook for testing the model on new sentences and performing translations.
- `translate.py`: Command-line tool for translating text with the trained model.
- `attention_visual.ipynb`: Jupyter notebook to visualize the attention layers and understand the model's focus during translation.
- `tokenizer_en.json`, `tokenizer_es.json`, `tokenizer_it.json`: Tokenizers for English, Spanish, and Italian languages.
- `weights/`: Directory to store trained model weights (this directory is ignored in version control via `.gitignore`).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sandeshtiwari/Machine-Translation-Transformer-from-Scratch.git
   cd Machine-Translation-Transformer-from-Scratch
   ```
