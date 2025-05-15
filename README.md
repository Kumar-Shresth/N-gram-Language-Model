# N-Gram Language Model with Interpolation

This project implements an optimized n-gram language model using unigram, bigram, and trigram probabilities with interpolation. The goal is to preprocess text data, train n-gram models using Maximum Likelihood Estimation (MLE) with Laplace smoothing, and optimize interpolation weights (λ values) to minimize perplexity. The final model is evaluated on a test set using perplexity as the performance metric.

---

## Features

- Text preprocessing including punctuation removal, stopword removal, and lemmatization.
- Training of unigram, bigram, and trigram models with Laplace smoothing.
- Interpolated n-gram model combining unigram, bigram, and trigram probabilities.
- Optimization of interpolation weights using grid search and `scipy.optimize.minimize()`.
- Efficient implementation with memory and time optimizations.

## How to Run

- Open the `main.ipynb` notebook in Jupyter Notebook or JupyterLab.
- Make sure to install the required Python packages (e.g., pandas, nltk, scipy) before running the notebook.
- Execute the cells in order to reproduce preprocessing, training, and evaluation steps.
