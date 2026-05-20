# Email Spam Classifier – SVM

A spam/ham email classifier built with **Support Vector Machines (SVM)** and a **Bag of Words** text representation. Also submitted to Kaggle — see [eladmoshe98](https://www.kaggle.com/eladmoshe98).

## Approach

- Text preprocessing: tokenization, stop-word removal, stemming
- Feature extraction: **Bag of Words** (CountVectorizer / TF-IDF)
- Primary classifier: **SVM** (linear kernel)
- Comparison classifiers: Naive Bayes, Logistic Regression, Random Forest

## Running

```bash
pip install scikit-learn pandas numpy jupyter
jupyter notebook spam_classifier.ipynb
```

## Tech Stack

Python · scikit-learn · pandas · NLTK
