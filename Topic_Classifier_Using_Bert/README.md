# 🧠 BERT Fine-Tuning for News Classification

## 📌 Project Overview

This project demonstrates how to fine-tune a transformer-based model (**BERT**) for **multi-class text classification** using the **AG News dataset**.

The goal is to classify news headlines into one of the following categories:
- World
- Sports
- Business
- Sci/Tech

This project covers the complete pipeline:
- Data loading & preprocessing
- Tokenization using BERT tokenizer
- Model fine-tuning using Hugging Face Transformers
- Evaluation using Accuracy & F1-score
- Deployment using Streamlit/Gradio for live predictions

---

## 🎯 Objectives

- Fine-tune `bert-base-uncased` for text classification  
- Apply tokenization and preprocessing techniques  
- Evaluate model performance using standard metrics  
- Build a simple UI for real-time predictions  

---

## 🗂 Dataset

- **Dataset Used:** AG News Dataset  
- **Source:** Hugging Face Datasets  

The dataset contains:
- News headlines (text)
- Corresponding category labels (4 classes)

---

## ⚙️ Tech Stack

- Python 🐍  
- Hugging Face Transformers 🤗  
- Datasets Library  
- PyTorch  
- Scikit-learn  
- Gradio  

---

## 🔄 Workflow

### 1. Data Loading
- Loaded AG News dataset using Hugging Face `datasets` library  



### 2. Tokenization
- Used `bert-base-uncased` tokenizer  
- Applied:
  - Padding
  - Truncation
  - Max sequence length  

---

### 4. Model Fine-Tuning
- Loaded pre-trained `bert-base-uncased`  
- Trained using Hugging Face `Trainer` API  
---

### 5. Evaluation

Model performance was evaluated using:

- ✅ Accuracy    
- ✅ F1-score  

These metrics help measure:
- Overall correctness (Accuracy)
- Balance between precision & recall (F1-score)

---

### 6. Deployment

The trained model is deployed using:

####  Gradio
- Interactive web interface  
- Real-time classification  

---

## 📊 Results

| Metric     | Score (Example) |
|-----------|----------------|
| Accuracy  | 0.941447       |
| F1 Score  | 0.941330       |

> Note: Actual scores may vary depending on training configuration.

---

## 💡 Key Learnings

- How transformer models like BERT work for NLP tasks  
- Transfer learning and fine-tuning techniques  
- Importance of tokenization in NLP pipelines  
- Model evaluation using multiple metrics  
- Deploying ML models for real-world usage  
