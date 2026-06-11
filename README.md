# fake-news-detector
## Fake News Detection using NLP & Machine Learning

A machine learning project that classifies news headlines as **Real or Fake**
using NLP techniques and Logistic Regression.

### How It Works
1. Text cleaned (lowercase, remove punctuation)
2. NLP: Stopword removal + Porter Stemming
3. TF-IDF Vectorization (text → numbers)
4. Logistic Regression with Sigmoid output
5. Threshold 0.5 → Fake (0) or Real (1)

### Dataset
FakeNewsNet — 23,000+ labeled news articles

### Accuracy
~90%+ on test data

## Tech Stack
- Python, Jupyter Notebook
- scikit-learn, NLTK, pandas, matplotlib

### Run Locally
pip install pandas scikit-learn nltk matplotlib seaborn
jupyter notebook Fake_News_Detection.ipynb
