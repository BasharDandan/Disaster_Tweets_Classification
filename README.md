## 📝 Project: Natural Language Processing (NLP) 

### Project Description
This project transitions from structural coordinate maps and computer vision pixels to processing natural language (text sequences). The primary objective of Natural Language Processing (NLP) here is to derive context and extract underlying information out of raw textual sequences, often referred to as sequence-to-sequence (seq2seq) and text classification problems.

### Problem Statement
The workspace focuses on processing textual datasets to build and evaluate multiple model types capable of classifying text strings. It systematically explores how computers process text by converting unstructured human characters into structured mathematical tensors.

### Core Processing Architectures & Concepts
* **Text Vectorization (Tokenization):** Mapping raw string sequences into discrete numerical tokens, setting vocab limits, and establishing standard sentence length padding.
* **Token Embeddings:** Moving past raw integer tokens to learn dense geometric vector representations where words with similar semantic meanings map closer together in a multi-dimensional embedding space.
* **Pre-trained Sentence Encoders:** Leveraging state-of-the-art architectures from **TensorFlow Hub** (such as the Universal Sentence Encoder) to translate complete text blocks into feature vectors without manual sequence processing.

### Evaluation Protocol
Models are rigorously benchmarked against standard sequence classification metrics. Custom statistical wrappers evaluate predictions based on:
