# Beyond Binary: BanglaMisinfoMGT

A multi-class multilingual misinformation detection project for identifying human-written and AI-generated fake/real news using traditional machine learning and transformer-based NLP models.

## Overview

This project focuses on misinformation detection across four classes:

- Human-written fake news
- Human-written real news
- Machine-generated fake news
- Machine-generated real news

The dataset was developed by collecting fake and real news samples and generating machine-written variants through LLM-based paraphrasing. The project compares traditional machine learning with transformer-based approaches to evaluate the importance of contextual language understanding in AI-generated misinformation detection.

## Methods

- Text preprocessing
- TF-IDF feature extraction
- SVM classification
- Transformer-based classification using XLM-RoBERTa
- Multilingual and cross-lingual evaluation

## Results

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| SVM + TF-IDF | 87.83% | - |
| XLM-RoBERTa | 98.18% | 98.13% |

XLM-RoBERTa achieved strong multilingual performance across Bangla, English, and code-mixed text.

## Technologies

Python, NLP, TF-IDF, SVM, XLM-RoBERTa, Transformers, Hugging Face, Machine Learning, Text Classification

## Kaggle Notebook

https://www.kaggle.com/code/devkawser/beyond-binary
