# 🎯 Next Word Prediction Project

This project builds a machine-learning model that predicts the next word in a given text sequence using LSTM / RNN architectures in Python.  
It also provides a simple web or desktop interface to see next-word predictions in action.

---

## 📌 Project Overview

The goal is to learn language patterns and forecast the most likely next word when given a partial text.  
Using text processing, sequence modeling and deep neural networks, the model produces next-word suggestions based on previous context.

---

## 📂 What’s Included

- `app.py` — A UI application built (Streamlit or similar) to input text and get predictions.  
- `tokenizer.pickle` — Tokenizer used to convert text to sequences.  
- `next_word_lstm.h5` — Pre-trained LSTM model file (or your model name).  
- `requirements.txt` — Dependencies required to run the project.  
- `README.md` — This file.  
- Other supporting files: e.g., `hamlet.txt`, `experiments.ipynb` (if present).

---

## 🛠 Tech Stack

- Python  
- TensorFlow / Keras (LSTM/RNN)  
- NumPy & Pandas  
- Streamlit (or whichever UI lib you used)  
- VS Code (for development)  

---

## 🔍 Workflow

### 1. Data Preparation  
- Load and clean text data (e.g., `hamlet.txt`).  
- Use tokenizer to convert words to sequences.  
- Pad sequences to fixed length.  

### 2. Model Architecture  
- Built an LSTM (or RNN) network that takes a sequence of words and predicts the next word.  
- Use embedding layer → LSTM layers → Softmax output.  
- Trained on your text corpus.

### 3. Deployment & UI  
- Built `app.py` to load the trained model and tokenizer.  
- User enters a sequence of text → model predicts next word.  
- UI shows results in real-time.

---

## 🚀 How to Run

### Clone the repo  
```bash
git clone https://github.com/Abhaypandy/Predicting_Next_word.git
# Predicting_Next_word
