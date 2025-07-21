# 📘 Word Embedding Similarity with GloVe

This project demonstrates how to use **pre-trained GloVe word embeddings** to compute **cosine similarity** between words. The goal is to find the top-N most similar words to a given query word.

---

### 📂 Files

- `main.ipynb`: Jupyter notebook with complete code and explanations.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project overview.

---

### 🚀 Changes made after Interview

- ✅ Real word vectors using **GloVe** (via `gensim`)
- ✅ Handles **out-of-vocabulary (OOV)** words gracefully
- ✅ Computes **cosine similarity** between words
- ✅ Returns top-N most similar words
- ✅ Clean and readable output formatting
- ✅ Ready to run in any environment

---

### 📚 Example Output

Top 3 most similar words to 'pear':
1. peach — Similarity: 0.7705
2. apples — Similarity: 0.6245
3. apple — Similarity: 0.5890

---

### 🛠️ Requirements

```bash
pip install -r requirements.txt
