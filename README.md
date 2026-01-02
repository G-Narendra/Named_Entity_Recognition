# 🔍 Named Entity Recognition (NER)
### Intelligent Information Extraction using Natural Language Processing

<p align="center">
<img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/NLP-SpaCy%20%7C%20NLTK-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Model-CRF%20%7C%20LSTM%20%7C%20BERT-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Optimized-brightgreen?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-Jupyter-orange?style=for-the-badge&logo=jupyter">
</p>

---

## 🌟 Overview

**Named Entity Recognition (NER)** is a fundamental task in Information Extraction that identifies and categorizes key information in unstructured text. This project implements an advanced NER pipeline capable of detecting entities such as **Persons (PER), Organizations (ORG), Locations (LOC), and Dates**. By utilizing a combination of statistical models and deep learning, the system transforms raw text into structured data ready for downstream analysis.



### Core Capabilities:
- **Entity Identification:** Detects spans of text representing specific categories.
- **Contextual Understanding:** Uses bi-directional context to accurately distinguish between ambiguous entities (e.g., "Apple" as a fruit vs. "Apple" as a company).
- **Multi-Model Support:** Implements traditional **CRF (Conditional Random Fields)** for speed and **LSTMs/Transformers** for state-of-the-art accuracy.
- **Scalable Extraction:** Optimized for processing large datasets (`ner_dataset.csv`) with minimal latency.

---

## 🧠 Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.8+ |
| **NLP Libraries** | SpaCy, NLTK, Transformers (Hugging Face) |
| **Deep Learning** | PyTorch / TensorFlow |
| **Data Handling** | Pandas, NumPy |
| **Environment** | Jupyter Notebook |

---

## 📁 Project Structure

```bash
Named_Entity_Recognition/
├── data/
│   └── ner_dataset.csv         # Annotated dataset for training (IOB format)
├── src/
│   └── NameEnitityRecognition.ipynb  # Main pipeline: preprocessing, training, & evaluation
├── assets/
│   └── confusion_matrix.png    # Performance analysis across entity classes
├── requirements.txt            # Dependency list
└── README.md                   # Documentation

```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone [https://github.com/G-Narendra/Named_Entity_Recognition.git](https://github.com/G-Narendra/Named_Entity_Recognition.git)
cd Named_Entity_Recognition

```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt

```

### 3️⃣ Run the Notebook

```bash
jupyter notebook NameEnitityRecognition.ipynb

```

---

## 💡 How It Works

The NER pipeline follows a specialized sequence-labeling workflow:

1. **Tokenization:** Breaking sentences into individual words or sub-word units.
2. **Feature Encoding:** Converting tokens into dense vectors using word embeddings (Word2Vec, GloVe, or BERT).
3. **Sequence Labeling:** The model predicts a label for each token (e.g., `B-PER`, `I-PER`, `O`) using context from previous and future tokens.
4. **Aggregation:** Reconstructing the labeled tokens into full entities.

---

## 📊 Performance & Evaluation

The model is evaluated using the **F1-Score**, which is the gold standard for NER due to the heavy imbalance of "O" (Outside) tags.

* **Precision:** Accuracy of the entities identified.
* **Recall:** Ability to find all relevant entities in the text.
* **Metrics Visualization:** Includes a per-entity breakdown (e.g., how well the model finds `LOC` vs `ORG`).

---

## 👨‍💻 Author

**Narendra (G‑Narendra)** AI | ML | Python | Full Stack | GenAI Enthusiast

📧 [Email Me](mailto:narendragandikota2540@gmail.com) | 💼 [LinkedIn](https://linkedin.com/in/g-narendra/) | 👨‍💻 [GitHub](https://github.com/G-Narendra)

🌐 [Portfolio](https://g-narendra-portfolio.lovable.app/)

---

<p align="center">⭐ If you find this project useful, feel free to give it a star! 🚀</p>

