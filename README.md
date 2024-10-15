# NLP for Social Sciences

This repository supplements the NLP for Social Sciences course taught during the fall semester of 2024 at the Université Lumière Lyon 2. 

Lecture/TD materials are stored in the `./n*` folders. You can run all Jupyter Notebooks locally or in Google Colab.

## Course Plan
1. Introduction to Natural Language Processing. Challenges of text processing (word ambiguity, idioms, slang, spelling wo). Existing applications of NLP (translation, trend analysis, summarization, virtual assistants). Text preprocessing steps. Lemmatization vs stemming. (CM 1) [Link](01-intro)
2. Vector representation of words. Embeddings obtained with one-hot encoding. Distributional hypothesis. Word-word co-occurrence and PMI matrices. Word-document matrices for tf-idf. Overview of word2vec models. (CM2) [Link](02-embeddings)
3. Basics of gradient descent for simple functions. Word embeddings using the `gensim` library. Visualization with t-SNE. (TD1) [Link](TD1)
4. Summary of approaches to vector representation. Negative sampling. Word2Vec: skip-gram vs CBOW. Linear operations with vectors, including addition and subtraction. Impact of large/small context window size on embedding results. Problem statement for text classification. Overview of feature extraction approaches: count-based vs neural. Overview of text classification with Naive Bayes. (CM3) [Link](03-embeddings-interpretability)


# TD 1

To run the notebooks on a cloud platform, just click on one of the badges in the table below:
| Topic                                     | Colab |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1 Preliminaries of gradient descent                             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD1/gradient_descent_preliminaries.ipynb)           |
| 2 Word embeddings                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD1/TD1_embeddings.ipynb)           |

# TD 2

| Topic                                     | Colab |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1 Supervised text classification                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD2/TD2_classification_supervisee.ipynb)           |
| 0 Text pre-processing                              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD1/TD1_text_preprocessing.ipynb)           |

Other Useful Resources:
1. https://perso.limsi.fr/anne/MRSD.html (in French)
2. https://web.stanford.edu/~jurafsky/slp3/ (in English)
