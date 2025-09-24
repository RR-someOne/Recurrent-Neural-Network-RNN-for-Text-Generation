# Recurrent Neural Network (RNN) for Text Generation
## Overview
This repository contains the implementation of a Recurrent Neural Network (RNN) designed for text generation. The project demonstrates how an RNN, a type of neural network well-suited for processing sequential data, can learn the patterns, grammar, and style of a given text corpus to generate new, coherent sentences and paragraphs. This is a foundational project for understanding a variety of natural language processing (NLP) tasks.

## Key Concepts
Recurrent Neural Networks (RNNs): These are a class of neural networks where connections between nodes form a directed graph along a temporal sequence. This allows the model to exhibit temporal dynamic behavior, making it ideal for tasks like text generation.

Sequential Data: The model is trained on a sequence of characters or words, learning the probability of the next character/word given the previous ones.

Training and Inference: The project includes scripts for both training the model on a custom dataset and for using the trained model to generate new text.

## Getting Started
To explore this project, you will need to set up your Python environment and acquire a text dataset for training.

## Prerequisites
Python 3.9 or higher

pip (Python package manager)

## Installation

<img width="763" height="464" alt="Screenshot 2025-09-24 at 11 03 15 AM" src="https://github.com/user-attachments/assets/f9032cf7-1b5a-4e00-ac36-685ce99a9a89" />
<img width="486" height="296" alt="Screenshot 2025-09-24 at 11 03 23 AM" src="https://github.com/user-attachments/assets/d9953ba9-79ec-4ad2-ac8a-ce3599560c2d" />

## How to Use
Prepare your data: Place your text corpus (e.g., a book, a collection of articles) in the data/ directory and name it text_corpus.txt.

Train the model: Run the training script to begin the learning process. You can adjust hyperparameters such as the number of epochs and batch size.

<img width="742" height="261" alt="Screenshot 2025-09-24 at 11 03 42 AM" src="https://github.com/user-attachments/assets/6adcee07-68b2-4d20-a8f2-5f4ced55a690" />
