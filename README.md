# Leveraging Pre-Trained Transformers for Sentiment Analysis: An Empirical Study on IMDb Movie Reviews

Guillaume-Le Gall Maela
MScT Data & Economics for Public Policy
École Polytechnique
maela.guillaume-le-gall@polytechnique.edu

## Abstract
This study evaluates the performance of transformer-based models in sentiment
analysis focusing on the IMDb Review Dataset, a widely used benchmark comprising 50,000 polarized movie reviews. While earlier research has employed classical
machine learning and deep learning models, recent advances in natural language
processing offer the potential for enhanced performance. I fine-tune DistilBERT (a
lightweight version of BERT) on the full IMDb dataset and assess its classification
accuracy relative to state-of-the-art approaches using the same dataset (notably
SVMs, CNNs and LSTMs). Minimal preprocessing is applied to preserve semantic
nuance and performance is measured using accuracy, precision, recall, F1-score
and confusion matrices. The resulting model achieves a test accuracy of 93.19%,
outperforming previous state-of-the-art approaches and illustrating the capability
of compressed transformer models to balance efficiency and performance.This
analysis suggests that pre-trained transformers, even in distilled form, provide a
compelling option for sentiment analysis tasks, especially when balanced against
training time and inference efficiency. Important limitations include the absence
of cross-validation and external domain testing, both of which offer avenues for
future investigation.
