**Readme : Fake News Detection using Bert and Dilbert**

📌 Overview

This project presents a Fake News Detection System built using BERT (Bidirectional Encoder Representations from Transformers).
The model is fine-tuned on a real-world dataset to classify news articles as Fake or Real.

🎯 Objective

To develop an intelligent system that can automatically identify fake news using Natural Language Processing (NLP) and Transformer-based deep learning models.

🧠 Methodology

The project follows a structured machine learning pipeline:

Dataset loading and exploration

Data preprocessing and cleaning

Tokenization using BERT tokenizer

Train-test split (80/20)

Fine-tuning pretrained BERT model

Model evaluation using standard metrics

Error analysis of misclassified samples

Model improvement using DistilBERT

Deployment using Gradio interface

📊 Dataset

Contains news articles labeled as Fake or Real

Total samples: ~800

Features used:

article_content → Input text

labels → Output (0 = Fake, 1 = Real)

The dataset is relatively balanced, ensuring fair model training.

🤖 Models Used
🔹 BERT (Primary Model)

bert-base-uncased

Fine-tuned for binary classification

🔹 DistilBERT (Improvement)

Lightweight and faster version of BERT

Used for performance comparison

⚙️ Technologies

Python

HuggingFace Transformers

PyTorch

Scikit-learn

Gradio

Google Colab

📈 Evaluation Metrics

The model performance is evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

🔍 Results

The model successfully classifies fake and real news

Achieves good performance on validation data

DistilBERT shows faster inference with comparable accuracy

❌ Error Analysis

Misclassifications occur due to:

Ambiguous or unclear language

Truncated long text sequences

Similar patterns in fake and real news

🚀 Deployment

A simple Gradio-based web application is implemented:

User enters news text

Model predicts:

✅ Real News

❌ Fake News

💡 Key Learnings

Understanding Transformer-based NLP models

Tokenization and text representation

Fine-tuning pretrained models

Model evaluation and improvement

Building end-to-end ML applications

Deploying models using Gradio
