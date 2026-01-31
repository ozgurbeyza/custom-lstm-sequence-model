# Sentiment Analysis Engine with Custom LSTM

## 🎯 Objective
To master the mathematical foundations of Sequence Modeling by implementing the internal gates of a Long Short-Term Memory (LSTM) network manually, avoiding high-level API abstractions, and applying it to Sentiment Analysis.

## 🚀 Key Features
* **From-Scratch LSTM Cell:** Manually implemented the forward pass logic for Forget, Input, and Output gates using linear algebra operations to handle vanishing gradient problems inherent in standard RNNs.
* **Semantic Vectorization:** Integrated Word2Vec embeddings to capture semantic relationships between words, reducing dimensionality while preserving context compared to one-hot encoding.
* **Sequence Processing:** Built a custom LSTM layer class to handle variable-length sequences via padding and processed time-series data for binary classification.
* **Dataset:** Analyzed the IMDB Movie Reviews dataset (10k+ samples) for binary sentiment classification.

## 📊 Results & Kaggle Performance
* **Test Accuracy:** 0.5081
* **F1-Score:** 0.6558
* **Kaggle Competition Score:** **0.538**

## 🛠 Tech Stack
* **Framework:** PyTorch (Low-level implementation)
* **NLP Tools:** Word2Vec, NLTK/Torchtext
* **Concepts:** Recurrent Neural Networks, Backpropagation through time.

---
*Note: This project demonstrates the "white-box" understanding of RNN architectures.*
