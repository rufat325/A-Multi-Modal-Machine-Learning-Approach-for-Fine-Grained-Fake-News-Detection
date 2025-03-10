# A-Multi-Modal-Machine-Learning-Approach-for-Fine-Grained-Fake-News-Detection
# Overview:

This repository contains the implementation of a multi-modal machine learning pipeline for fine-grained fake news detection. The project leverages text and image embeddings using BERT and CLIP models to classify news into six categories, including "Real," "Textual Fabrication," and "Visual Manipulation." The model was trained and evaluated on the FineFake dataset, achieving an accuracy of 62.6%.

# Features:

Preprocessing for both textual and visual data.
Multi-modal feature fusion with domain-adversarial training for cross-platform generalization.
Fine-grained classification into six distinct categories of fake news.
Evaluation metrics: Accuracy, Precision, Recall, F1-Score.
Dataset
The project uses the FineFake dataset, which includes over 16,000 news articles with associated images. For privacy and copyright considerations, the dataset is not included in this repository. Instructions for accessing the dataset are provided below.

# Dataset Labels:

Real: Verified news.

Text-Image Inconsistency: Contradictions between text and images.

Content-Knowledge Inconsistency: Contradictions with external knowledge.

Textual Fabrication: Fabricated or misleading text.

Visual Manipulation: Doctored or misleading images.

Other: Miscellaneous fake news cases.
