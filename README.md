# IMDB Sentiment Analysis (RNN)

This project performs sentiment analysis on the IMDB movie reviews dataset using Deep Learning (Embedding + SimpleRNN).  
The model predicts whether a review is **Positive** or **Negative**.

## Features
- Text preprocessing (tokenization + padding)
- Word Embedding layer
- SimpleRNN model for sequence learning
- Binary classification output (sigmoid)

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Jupyter Notebook

## Files
- `embedding.ipynb` → Embedding layer + preprocessing
- `simpleRNN.ipynb` → SimpleRNN model training
- `prediction.ipynb` → Testing predictions on sample reviews
- `main.py` → Main script (can be used for deployment)
- `simple_rnn_imdb.h5` → Saved trained model

## How to Run
### 1. Install dependencies
### 2. run streamlit main.py

```bash
pip install tensorflow numpy pandas
