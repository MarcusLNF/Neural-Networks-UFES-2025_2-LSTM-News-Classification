# Neural Networks | UFES-2026/2 | LSTM: News Classification

# News Classification with LSTM Networks

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![NLP](https://img.shields.io/badge/Topic-Natural%20Language%20Processing-purple)
![LSTM](https://img.shields.io/badge/Model-LSTM-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Academic%20Project-lightgrey)

This repository contains an implementation of a **Long Short-Term Memory (LSTM) neural network** for **news text classification**, developed as part of a **Neural Networks coursework assignment**.

The project explores the application of **deep learning techniques for Natural Language Processing (NLP)** using **PyTorch**, focusing on sequence modeling and text classification.

---

# Objective

The objective of this project is to build a **deep learning model capable of classifying news articles into predefined categories**.

The project covers the complete NLP workflow, including:

- Text preprocessing
- Vocabulary creation
- Sequence encoding
- LSTM-based neural network design
- Model training and evaluation

This approach demonstrates how **recurrent neural networks can learn contextual patterns in textual data**.

---

# Project Workflow

The notebook follows a typical **NLP deep learning pipeline**.

## 1. Dataset Loading

The dataset contains news articles labeled according to their category.

Key steps include:

- Loading the dataset
- Inspecting sample texts
- Preparing labels for classification

---

## 2. Text Preprocessing

Before training the neural network, the textual data must be processed.

Common preprocessing steps include:

- Lowercasing text
- Tokenization
- Removing unnecessary characters
- Converting text into numerical representations

The text is transformed into sequences of integers representing tokens in the vocabulary.

---

## 3. Vocabulary Construction

A vocabulary is created to map words to numerical indices.

This allows the neural network to process text as **sequences of integers**.

Key elements:

- Word-to-index mapping
- Handling unknown tokens
- Sequence padding to ensure uniform input length

---

# Model Architecture

## LSTM Network

The classification model is based on a **Long Short-Term Memory (LSTM) network**, which is designed to capture dependencies in sequential data.

The architecture typically includes:

- **Embedding Layer** – converts word indices into dense vector representations
- **LSTM Layer** – processes sequences and captures contextual information
- **Fully Connected Layer** – maps learned features to output classes
- **Softmax Output Layer** – produces class probabilities

LSTM networks are particularly effective for **sequence modeling tasks such as text classification**.

---

# Training Process

The training process involves:

- Forward propagation through the network
- Loss computation using a classification loss function
- Backpropagation through time (BPTT)
- Parameter updates using an optimizer

Training progress is monitored through:

- Training loss
- Validation performance

---

# Model Evaluation

The model is evaluated on a **test dataset** to measure its ability to generalize.

Typical evaluation metrics include:

- Classification accuracy
- Loss analysis
- Prediction examples

---

# Technologies Used

- **Python**
- **PyTorch**
- **NumPy**
- **Jupyter Notebook**

---

# How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```
2. Navigate to the project folder
```bash
cd your-repository
```
3. Open the notebook
```bash
jupyter notebook
```
or
```bash
jupyter lab
```
4. Run the cells sequentially.

---

# Author
Marcus Louriçal Neves Filho
Computer Science Undergraduate
Federal University of Espírito Santo (UFES)
