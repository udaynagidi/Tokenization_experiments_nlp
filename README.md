# Tokenization Experiments – NLP Preprocessing in Python

## 📌 Project Overview
This Jupyter Notebook focuses on the process of *tokenization* — the foundation of most Natural Language Processing workflows.  
The project experiments with different Python libraries and techniques to tokenize raw text and analyze how tokens differ across methods.  
It includes both *statistical and visual evaluation* of token structures to support informed preprocessing decisions in future NLP projects.

---

## 📊 Dataset Description
This project uses sample raw text data, including:
- Sentences with punctuation
- Texts with contractions and special characters
- Multi-paragraph string blocks

The dataset is either hardcoded within the notebook or simulated to demonstrate preprocessing behavior across edge cases.

---

## 📈 Visualizations Used
- *Token Count Distribution Bar Charts*
- *Word Cloud of Frequent Tokens*
- *Comparative Tables of Token Outputs*
- *Line Plots (if analyzing sequence positions)*
- *Histogram of token lengths (optional)*

---

## 🔍 Key Insights
- Tokenization strategies (e.g., NLTK, spaCy, regex) produce different outputs for the same input.
- spaCy tends to preserve context better with its syntactic awareness.
- Simple whitespace or regex tokenizers can split important linguistic constructs (e.g., “don’t” becomes [“don”, “’t”]).
- Visualization reveals how token length and count vary significantly by method and use case.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://colab.research.google.com/drive/1wZG7Ht_nNenWlp7w5KiQJnchJOzlHR98?usp=sharing
