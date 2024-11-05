# NLP for Social Sciences

This repository supplements the NLP for Social Sciences course taught during the fall semester of 2024 at the Université Lumière Lyon 2. 

Lecture/TD materials are stored in the `./n*` folders. You can run all Jupyter Notebooks locally or in Google Colab.

## Course Plan
1. Introduction to Natural Language Processing. Challenges of text processing (word ambiguity, idioms, slang, spelling wo). Existing applications of NLP (translation, trend analysis, summarization, virtual assistants). Text preprocessing steps. Lemmatization vs stemming. (CM 1) [Link](01-intro)
2. Vector representation of words. Embeddings obtained with one-hot encoding. Distributional hypothesis. Word-word co-occurrence and PMI matrices. Word-document matrices for tf-idf. Overview of word2vec models. (CM2) [Link](02-embeddings)
3. Summary of approaches to vector representation. Negative sampling. Word2Vec: skip-gram vs CBOW. Linear operations with vectors, including addition and subtraction. Impact of large/small context window size on embedding results. Problem statement for text classification. Overview of feature extraction approaches: count-based vs neural. Overview of text classification with Naive Bayes. (CM3) [Link](03-embeddings-interpretability)
4. Overview of feature extraction approaches: count-based vs neural. Text classification with Naive Bayes. Laplace (add-one) smoothing. Text classification with Logistic Regression. Training: Maximizing Likelihood. Naïve Bayes vs Logistic Regression. Text classification with SVM. Overview of classification with Neural Networks. A variety of word embeddings. Data Augmentation for Text. (CM4) [Link](04-supervised-classification)
5. Neural Networks. Fully-connected neural networks. Transformer models. Encoders and decoders. Attention Mechanism. BERT family of models. GPT family of models. Text classification with Logistic Regression. Training: Maximizing Likelihood. Naïve Bayes vs Logistic Regression. Modern GPT-3 models: prompting. Risks and limitations of current LMs. (CM5) [Link](05-language-modelling)

# TD 1

To run the notebooks on a cloud platform, just click on one of the badges in the table below:
| Topic                                     | Colab |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1 Preliminaries of gradient descent                             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD1-embeddings/gradient_descent_preliminaries.ipynb)           |
| 2 Word embeddings                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD1-embeddings/TD1_embeddings.ipynb)           |

# TD 2

| Topic                                     | Colab |
|:--------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1 Supervised text classification                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD2-supervised-classification/TD2_classification_supervisee.ipynb)           |
| 0 Text pre-processing                              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD1-embeddings/TD1_text_preprocessing.ipynb)           |

# TD 3

Aurora-embeddings [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD3-Aurora-sentence-embeddings/TP_Arora_M1MIASHS%20Correction.ipynb)
# TD 4

| Topic     |                                                                                    Colab                                                                                     |
|:----------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1 Mistral | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD4-mistral-rag/Mistral.ipynb) |
| 2 OLLaMA  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/upunaprosk/ul2-nlp-course/blob/2024/TD4-mistral-rag/Ollama.ipynb)  |

___
Useful links for the course:
1. https://web.stanford.edu/~jurafsky/slp3/ (in English)
2. Official course by Hugging-Face: https://huggingface.co/learn/nlp-course/fr

