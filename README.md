# Word2Vec using Game of Thrones Text

## Overview

This project demonstrates the implementation of **Word2Vec** using text data from the *Game of Thrones* book series. The notebook explores natural language processing (NLP) concepts such as text preprocessing, tokenization, training word embeddings, and finding semantic relationships between words.

The goal is to understand how Word2Vec captures contextual meaning and represents words in vector space.

---

## File

* `word2Vec(GOT text book).ipynb` — Main Jupyter Notebook containing preprocessing, model training, and analysis.

---

## Features

* Text preprocessing and cleaning
* Sentence tokenization
* Training a Word2Vec model using `gensim`
* Generating word embeddings
* Finding similar words
* Vector representation of characters and locations
* Basic semantic analysis

---

## Technologies Used

* Python
* Jupyter Notebook
* Gensim
* NLTK
* NumPy
* Pandas

---

## Dataset

The dataset consists of text extracted from the *Game of Thrones* books.

Example use cases:

* Character relationship analysis
* Similarity between locations or families
* Context-based word understanding

---

## Installation

Install the required libraries before running the notebook:

```bash
pip install gensim nltk pandas numpy
```

---

## How to Run

1. Clone the repository or download the notebook.
2. Open Jupyter Notebook.
3. Run:

```bash
jupyter notebook
```

4. Open `word2Vec(GOT text book).ipynb`.
5. Execute all cells sequentially.

---

## Example Operations

### Find Similar Words

```python
model.wv.most_similar('jon')
```

### Word Vector

```python
model.wv['winterfell']
```

---

## Learning Outcomes

By completing this project, you will understand:

* Basics of NLP preprocessing
* Word embeddings and vector representations
* Contextual similarity between words
* Practical implementation of Word2Vec

---

## Future Improvements

* Add visualization using t-SNE or PCA
* Train on larger fantasy datasets
* Compare CBOW and Skip-Gram architectures
* Build character relationship graphs

---

## Author

Ashish Kumar
