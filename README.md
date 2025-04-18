# 📝 Text Summarization Project

This repository explores two approaches to text summarization: a **traditional TF-IDF-based extractive method** and a **transformer-based abstractive summarizer using Google's T5 (Text-To-Text Transfer Transformer)**.

## 📌 Overview

Text summarization is the process of distilling the most important information from a source to produce a condensed version. This project aims to compare extractive summarization techniques with modern deep learning-based abstractive methods.

### 🔍 Methods Covered

- **Preprocessing & Normalization**: Cleaning, lowercasing, punctuation removal, stop word removal, tokenization, and stemming/lemmatization.
- **TF-IDF Based Summarization**: 
  - Converts text to TF-IDF vectors.
  - Ranks sentences based on importance.
  - Extracts top sentences as a summary.

- **Abstractive Summarization Using T5**:
  - Fine-tuned version of the T5 model from Hugging Face Transformers.
  - Generates new sentences that summarize the text in a human-like manner.

---

🧠 Models & Tools Used
T5 Transformer

NLTK / spaCy for preprocessing

Scikit-learn for TF-IDF

Hugging Face Transformers for model loading

🧪 Evaluation (Optional)
You can evaluate summaries using:

ROUGE Score

BLEU Score

Manual evaluation (for semantic quality)

📚 References
T5 Paper

Hugging Face Transformers

TF-IDF in NLP

✨ Future Work
Add BART summarizer

Build a Streamlit web interface

Deploy to Hugging Face Spaces

🧑‍💻 Author
Your Name – @JamesMungai254

📄 License
This project is licensed under the MIT License.




