**Sentiment Analysis of Movie Reviews using Deep Learning Models**

**Project Overview**
This project focuses on sentiment analysis, a key task in Natural Language Processing (NLP), using the powerful Global Vectors for Word Representation (GloVe) model, with two deep learning models: RNN and CNN.
The objective is find out which deep learning model is best suitable to accurately classify text data, such as movie reviews or customer feedback, into different sentiment categories (positive or negative).

**Features**
**Pre-Processing Text Data:** Tokenization, stopword removal, lemmatization, and handling negations to prepare the dataset for modeling.
**GloVe Word Embeddings:** Utilization of pre-trained GloVe embeddings for robust feature representation of text.
**Neural Network Model:** Implementation of a Sequential model in TensorFlow with an Embedding layer initialized with GloVe vectors.
**Handling Polysemy:** Enhanced ability to handle words with multiple meanings through contextual word representations.
**Efficiency and Accuracy:** Pre-trained embeddings improve model efficiency and contribute to higher accuracy in sentiment classification.

**Dataset**
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. There are 25,000 highly polar movie reviews for training, and 25,000 for testing.
Find the dataset on: http://ai.stanford.edu/~amaas/data/sentiment/

**Tools and Technologies:**
Python
TensorFlow and Keras
NLTK for text preprocessing
GloVe word embeddings
