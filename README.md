# Data Science & Machine Learning Portfolio

> **Ivan Acosta** — University Lecturer | Data & AI Practitioner

---

## About Me

I am a university lecturer and data/AI practitioner with experience in machine learning, deep learning, and natural language processing. I design and deliver courses that bridge academic theory with real-world industry practice. This portfolio showcases my teaching materials and applied projects, organized so that both technical and non-technical reviewers — including HR professionals and academic committees — can easily navigate and evaluate my work.

All notebooks are ready to run in **Google Colab** with a single click; no local setup is required.

---

## Repository Structure

| Folder | Description |
|---|---|
| [`machine-learning/`](./machine-learning/) | Classical ML algorithms, feature engineering, and model evaluation |
| [`deep-learning/`](./deep-learning/) | Neural networks, CNNs, RNNs, and transfer learning with TensorFlow/PyTorch |
| [`nlp/`](./nlp/) | Text classification, sentiment analysis, embeddings, and transformer-based models |
| [`teaching-materials/`](./teaching-materials/) | Lecture slides, exercises, and guided notebooks used in university courses |

---

## Example Projects

| Project | Folder | Description |
|---|---|---|
| House Price Prediction | `machine-learning/` | End-to-end regression pipeline using scikit-learn and feature engineering |
| Customer Churn Classification | `machine-learning/` | Binary classification with ensemble methods and SHAP explainability |
| Image Classification with CNNs | `deep-learning/` | Convolutional neural network trained on CIFAR-10 using TensorFlow/Keras |
| Sentiment Analysis with LSTMs | `deep-learning/` | Sequence modelling for movie review sentiment using recurrent networks |
| Text Classification with BERT | `nlp/` | Fine-tuning a pre-trained BERT model for multi-class text categorisation |
| Named Entity Recognition | `nlp/` | Token-level NER using spaCy and a custom-trained transformer |
| Intro to Machine Learning (Course) | `teaching-materials/` | Full module with slides, exercises, and guided Colab notebooks |
| Python for Data Science (Workshop) | `teaching-materials/` | Hands-on workshop covering pandas, matplotlib, and scikit-learn basics |

---

## How to Run the Notebooks

Every notebook in this repository includes a **"Open in Colab"** badge at the top. Click it to open the notebook directly in [Google Colab](https://colab.research.google.com/) — no installation needed.

If you prefer to run notebooks locally:

```bash
# 1. Clone the repository
git clone https://github.com/ivanacostag02/data-science-ml-portfolio.git
cd data-science-ml-portfolio

# 2. Create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# 3. Install common dependencies
pip install numpy pandas matplotlib scikit-learn tensorflow torch transformers
```

Then open the desired `.ipynb` file with `jupyter notebook` or `jupyter lab`.

---

## License and Usage

The code in this repository is released under the **MIT License**.  
This means you are free to use, modify, and share the code, provided that you include the original copyright notice and license.

All notebooks and materials are primarily intended for **educational purposes**, such as teaching, learning, and demonstrating data science and machine learning concepts.  
If you use or adapt these materials in your own courses, talks, or projects, a brief attribution to the original author is appreciated.

See the [LICENSE](./LICENSE) file for full details.

