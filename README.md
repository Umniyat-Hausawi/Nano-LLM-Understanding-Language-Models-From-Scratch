# 🧠 Nano-LLM: Understanding Language Models from Scratch

Understanding Language Models by Progressively Building Bigram Models, Context-Aware Models, and Transformers using PyTorch.

---

## 📌 Project Overview

This project explores how language models work internally by progressively building increasingly capable language models from scratch using PyTorch.

Instead of relying on pre-trained APIs or ready-made LLMs, this project focuses on understanding the fundamental mechanics behind language generation, including tokenization, numerical representation, next-token prediction, training loops, context learning, self-attention, and text generation.

The project follows a step-by-step educational progression from simple language modeling approaches to Transformer-based architectures.

---

## 🎯 Project Goal

The primary goal of this project is to deeply understand how language models learn from text by progressively building multiple language modeling approaches from scratch.

Rather than focusing only on model performance, this project emphasizes understanding the evolution of language modeling:

**Simple Statistical Prediction → Context Learning → Transformer Architectures**

Key questions explored:

- How does raw text become numerical input?
- How do language models learn token relationships?
- Why is context important for language generation?
- Why do Transformer architectures outperform simpler models?
- How do tokenization strategies affect generated text quality?

---

## ⚙️ Project Pipeline

```text
Raw Text Dataset
↓
Dataset Inspection & Subset Selection
↓
Minimal Text Preprocessing
↓
Character-Level Tokenization
↓
Vocabulary Building
↓
Encoding & Decoding
↓
Training Sequence Creation
↓
Character-Level Bigram Model
↓
Bigram Training & Evaluation
↓
Context-Aware Character Model
↓
Context Model Training & Evaluation
↓
Subword Tokenization (BPE)
↓
Subword-Based Context Model
↓
Transformer Components
(Token Embeddings → Positional Embeddings → Self-Attention → Multi-Head Attention → Feed Forward Networks)
↓
Full Transformer Model
↓
Transformer Training & Evaluation
↓
Text Generation Comparison
↓
Final Model Analysis
```

---

## 🧩 Models Implemented

### 1. Character-Level Bigram Language Model

Built a simple Bigram model to understand the core principle of:

> Next-token prediction

This model learns token-to-token transition probabilities while exposing the limitations of short-context language modeling.

---

### 2. Context-Aware Character Model

Improved the Bigram approach by introducing context windows.

This model learns longer token dependencies and generates more coherent text than a simple Bigram model.

---

### 3. Subword Tokenization using BPE

Implemented Byte Pair Encoding (BPE) tokenization to move beyond character-level representations.

This improves token efficiency and helps the model learn more meaningful language units.

---

### 4. Tiny Transformer Model

Built a mini Transformer architecture from scratch using PyTorch.

Implemented core Transformer components:

- Token Embeddings
- Positional Embeddings
- Self-Attention
- Multi-Head Attention
- Feed Forward Networks
- Residual Connections
- Layer Normalization
- Transformer Blocks

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Datasets
- Tokenizers (BPE)
- Google Colab / Jupyter Notebook

---

## 📂 Dataset

This project uses the TinyStories dataset for educational language modeling.

TinyStories was selected because it provides:

- Simple grammatical structures
- Repetitive language patterns
- Smaller vocabulary size
- Faster experimentation for educational LLM development

---

## 📚 Key Learning Outcomes

Through this project, I gained practical understanding of:

- Tokenization strategies
- Vocabulary creation
- Encoding & decoding pipelines
- Next-token prediction
- Cross entropy loss in language modeling
- Context windows and sequence modeling
- Embeddings and vector representations
- Self-attention mechanisms
- Transformer architecture fundamentals
- Text generation workflows

---

## 📊 Results & Insights

This project demonstrates an important progression:

> As language models gain better token representations and stronger context understanding, text generation quality improves significantly.

Comparing Bigram, Context-Aware, Subword, and Transformer models helped illustrate:

- Why simple language models struggle
- Why context matters
- Why tokenization choices affect quality
- Why Transformers became the dominant architecture behind modern LLMs

---

## 📁 Repository Structure

```text
├── Nano_LLM_Understanding_Language_Models_from_Scratch.ipynb
├── README.md
└── outputs / generated text samples
```

---

## 🚀 Future Improvements

- Larger datasets
- Better hyperparameter tuning
- Longer context windows
- Larger Transformer architecture
- Fine-tuning experiments

---

## 👩‍💻 Author

**Umniyat Hausawi**  
**AI Engineer | Machine Learning, Deep Learning & NLP Projects**
