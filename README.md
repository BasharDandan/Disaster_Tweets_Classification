## 📝 Disaster tweets classification using NLP and TensorFlow

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

### Technologies Used
Python

TensorFlow & Keras Applications

TensorFlow Hub

NumPy

Pandas

Matplotlib

Scikit-Learn

### Model Architecture
The text classification benchmark pipeline evaluates multiple deep sequential architectures:

Baseline Pipeline: TF-IDF Vectorization mapped into a Multinomial Naive Bayes classifier.

Dense Feed-Forward Topology: Fully connected layer sequences acting on a custom token-embedded representation.

Recurrent Sequence Layers: Bidirectional LSTMs and GRU cells tracking structural spatial correlations backwards and forwards.

1D Convolutional Networks: Passing localized Conv1D spatial kernels across token dimensions to pick up adjacent word phrases (N-grams).

Transfer Learning Backbones: Deploying a pre-trained sentence encoder wrapper from TensorFlow Hub to generate contextualized vector arrays directly from raw textual sentences.

### Results
The pre-trained structural sentence transformer models outperformed baseline sequential wrappers by mining complex context out of conversational text strings.

Models were evaluated using rigorous verification arrays:

Accuracy: Overall correctness matrix.

Loss: Binary Crossentropy performance curves.

F1-Score / Precision / Recall: Tracking false positive and false negative balances across text classifications.

### How To Run
Clone this repository onto your workstation.

Install deep learning and token processing packages: pip install tensorflow numpy pandas matplotlib scikit-learn tensorflow-hub

Launch Jupyter Notebook and navigate to NLP_in_TensorFlow.ipynb.

Execute cells sequentially to verify text token boundaries and track validation metric transformations.

### Future Improvements
Expand token architectures to utilize full BERT transformers or fine-tuned sequence-to-sequence (seq2seq) text structures.

Implement character-level sequence processing layers to handle misspelled tokens or unstructured noise.

Scale up text pipelines using multi-class arrays to evaluate multi-label text classification scenarios.

