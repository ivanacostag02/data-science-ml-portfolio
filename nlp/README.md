# Natural Language Processing (NLP)

This folder contains notebooks and projects focused on **Natural Language Processing (NLP)** — the field of AI that enables computers to understand, interpret, and generate human language.

Projects range from classical text processing techniques to modern transformer-based models (BERT, GPT-style architectures). All notebooks run in **Google Colab** — click the badge at the top of any notebook to open it instantly.

---

## Topics Covered

- Text preprocessing: tokenisation, stemming, lemmatisation, stopword removal
- Bag-of-Words and TF-IDF representations
- Word embeddings: Word2Vec, GloVe, FastText
- Text classification and sentiment analysis
- Named Entity Recognition (NER)
- Topic modelling with LDA
- Fine-tuning transformer models (BERT, DistilBERT) with Hugging Face
- Sequence-to-sequence tasks: summarisation and translation

---

## Projects

| Notebook | Description |
|---|---|
| `text_classification_bert.ipynb` | Fine-tuning a pre-trained BERT model for multi-class text categorisation using Hugging Face |
| `sentiment_analysis_classical.ipynb` | Sentiment classification using TF-IDF and logistic regression as a strong baseline |
| `named_entity_recognition.ipynb` | Token-level NER using spaCy and a fine-tuned transformer model |
| `topic_modelling_lda.ipynb` | Discovering latent topics in a news article dataset using Latent Dirichlet Allocation |
| `text_summarisation.ipynb` | Abstractive text summarisation using a pre-trained sequence-to-sequence model (T5) |
| `word_embeddings_exploration.ipynb` | Visualising and exploring Word2Vec and GloVe embeddings with dimensionality reduction (TSNE) |

---

## How to Run

1. Open any notebook in this folder.
2. Click the **"Open in Colab"** badge at the top of the notebook.
3. For transformer-based notebooks, enabling GPU is recommended: `Runtime → Change runtime type → GPU`.
4. Run all cells from top to bottom (`Runtime → Run all`).

No local installation is required. All dependencies are installed within the notebook.

---

## Requirements

When running locally, the following packages are used:

```
numpy
pandas
matplotlib
scikit-learn
nltk
spacy
gensim
transformers
torch
datasets
```

Install them with:

```bash
pip install numpy pandas matplotlib scikit-learn nltk spacy gensim transformers torch datasets
```

---

*Back to [main portfolio](../README.md)*
