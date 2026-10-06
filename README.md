# Task 5 – Deep Learning NLP Text Classifier

## 📌 Project Overview

This project is part of the **RABTECH Academy AI/ML program**.

The objective of this task is to build a **Deep Learning NLP text classifier** that can classify movie reviews as either **positive** or **negative**.

The project uses the **ACL IMDB dataset** and a neural-network-based sentiment classification model built with **TensorFlow/Keras**.

---

## 🎯 Objectives

- Load and prepare the ACL IMDB movie review dataset.
- Perform text preprocessing and vectorization.
- Build a deep learning NLP classification model.
- Train the model using training and validation data.
- Evaluate the model on unseen test data.
- Generate predictions and classification metrics.
- Visualize training and validation performance.
- Save the trained model for future use.

---

## 📂 Dataset

The project uses the **ACL IMDB movie review dataset**.

The dataset contains:

- **25,000 training reviews**
- **25,000 test reviews**
- Two sentiment classes:
  - `0` → Negative
  - `1` → Positive

Dataset source:

Stanford AI Lab – Large Movie Review Dataset  
https://ai.stanford.edu/~amaas/data/sentiment/

---

## 🛠️ Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 🧠 Model Architecture

The sentiment classifier uses the following architecture:

1. **TextVectorization**
   - Vocabulary size: 20,000
   - Sequence length: 200

2. **Embedding Layer**
   - Embedding dimension: 64

3. **Global Average Pooling**

4. **Dense Layer**
   - 64 neurons
   - ReLU activation

5. **Output Layer**
   - 1 neuron
   - Sigmoid activation

The model uses:

- **Adam optimizer**
- **Binary Cross-Entropy loss**
- **Accuracy** as the evaluation metric

---

## 🔄 Project Workflow

```text
ACL IMDB Dataset
        ↓
Load Movie Reviews
        ↓
Create DataFrames
        ↓
Train / Validation / Test Split
        ↓
Text Vectorization
        ↓
Embedding Layer
        ↓
Global Average Pooling
        ↓
Dense Neural Network
        ↓
Sentiment Prediction
        ↓
Model Evaluation
        ↓
Save Trained Model
