# 🧠 Spam Classifier with PyTorch

This project demonstrates a simple neural network built with PyTorch to classify messages as **spam** or **ham** (not spam). The goal is to explore the full machine learning pipeline: preprocessing, model design, training, and evaluation.

---

## 📌 Overview

- Language: Python
- Framework: PyTorch
- Task: Binary Text Classification (Spam vs. Ham)
- Data: A small, custom text dataset (for experimentation purposes)

---

## 🚀 Project Structure

```bash
📁 spam-classifier/
├── data/                   # Folder containing the dataset
├── spam_classifier.ipynb   # Main notebook with full code
├── README.md               # This file
└── requirements.txt        # (Optional) Python dependencies
```

---

## 📖 What you'll learn

- How to preprocess raw text into numerical vectors using CountVectorizer

- How to create a custom neural network using torch.nn.Module

- How to train and evaluate a binary classifier

- How to use DataLoaders for batching

- How to interpret the loss function and accuracy

## ⚙️ How to run
1. Clone this repo: (Use SSH key)
```
git clone git@github.com:CodriXAI/spam-classifier.git
cd spam-classifier
```
2. Create a virtual environment (optional but recommended):
```
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Open the notebook:
```
jupyter notebook spam_classifier.ipynb
```

## 📄 License
This project is for educational purposes only.

## Autor
- Cristian "CodriX" Colares - A R
