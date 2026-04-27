📌 Next Word Prediction (BiLSTM)
🚀 Overview

This project builds a Next Word Prediction model using Natural Language Processing (NLP) and Deep Learning.
The model is trained on a text dataset and predicts the most likely next word for a given input sequence.

🧠 Approach
Loaded and read text dataset
Performed tokenization using Keras Tokenizer
Generated input sequences
Applied padding to make sequences equal length
Trained a Bidirectional LSTM (BiLSTM) model
⚙️ Model
Embedding Layer
Bidirectional LSTM
Dropout
LSTM
Dense (Softmax)
▶️ Usage
Input a sequence of words
Model predicts the next probable word
🛠️ Tech Stack
Python
TensorFlow / Keras
NumPy
📌 Output

Given a sentence, the model predicts the next word based on learned patterns from the dataset.
