# 🔍 Named Entity Recognition (NER)

**Extracting named entities (persons, organizations, locations) from text using deep learning.**

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![License MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

---

## 🎯 Problem Statement

Extracting named entities (persons, organizations, locations) from text using deep learning.

---

## 📊 What I Built

LSTM-based NER pipeline: data preprocessing, token indexing, padding, LSTM model training, entity extraction.

### Key Results

| Metric | Value |
|---|---|
| **Model** | LSTM with Keras/TensorFlow |

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| **Language** | Python 3.8+ |
| **Framework** | LSTM with Keras/TensorFlow |

---

## 📁 Project Structure

```
Named_Entity_Recognition/
├── *.ipynb                          # Main notebook
├── README.md
└── LICENSE
```

---

## 🔧 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook *.ipynb
```

---

## ⚠️ Limitations

- **No CRF layer**
- **No pre-trained embeddings**
- **No confidence scores**
- **Limited to CoNLL format**

---

## ⚠️ Disclaimer

This is an educational project for learning NLP concepts. It is not intended for production use.

---

*Built as part of MSc Data Science coursework.*
