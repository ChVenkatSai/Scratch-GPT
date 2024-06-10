# Scratch-GPT
This repository contains Scratch GPT, a Generative Pretrained Transformer model built entirely from scratch. The model's architecture includes word and positional embeddings, multi-headed self-attention mechanisms, and stacked Transformer blocks. It is trained on Jane Austen's 'Pride and Prejudice' but can be retrained with various corpuses. 

## Features

- **Word Embeddings**: Converts input tokens into dense vectors.
- **Positional Embeddings**: Adds positional information to input tokens to capture the order of the sequence.
- **Multi-Headed Self-Attention**: Allows the model to focus on different parts of the input sequence for each head, capturing complex dependencies.
- **Transformer Blocks**: Stacked layers of normalization, attention, and feed-forward networks to build deep representations.
- **Output Layer**: Fully connected layer to generate probabilities for the next token in the sequence.

## Training Data
The model was trained on the text from the Gutenberg Project's version of Jane Austen's novel "Pride and Prejudice". This rich and nuanced text helps the model to learn and generate sophisticated language patterns.

## Run
To use this project, open it colab and run it with a GPU.
