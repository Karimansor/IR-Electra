# IR-Electra

Fine-tuning a pre-trained ELECTRA model for document relevance classification in Information Retrieval (IR).

---

## Project Overview

This repository demonstrates how to fine-tune the ELECTRA transformer model to classify the relevance of documents given a query. The task is to predict whether a document is relevant (label `1`) or non-relevant (label `0`) to a query in an IR setting.

---

## Features

- **Synthetic Dataset Generation:**  
  Creates query-document pairs across three categories: Sports, Tech, and Health. Each pair is labeled as relevant or non-relevant.

- **Custom Dataset Preprocessing:**  
  Implements a custom PyTorch dataset class to tokenize query-document pairs and prepare inputs for ELECTRA.

- **Model Fine-Tuning:**  
  Fine-tunes the ELECTRA model on the synthetic dataset for binary relevance classification.

- **Evaluation:**  
  Evaluates model accuracy on a held-out test set.

---

