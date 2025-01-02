# Text Summarization Techniques

This repository contains implementations for both extractive and abstractive text summarization techniques. These techniques are used to generate concise and coherent summaries from longer text inputs.

The project includes two distinct methods for text summarization:

1. **Extractive Summarization**:
   - This method selects sentences directly from the input text to form a summary.
   - It utilizes techniques like Word Frequency and TF-IDF for scoring sentence relevance.
   - The extractive summarization implementation is based on NLP techniques, including tokenization, word frequency analysis, and TF-IDF.

2. **Abstractive Summarization**:
   - This method generates new sentences that paraphrase the important information in the text.
   - The implementation uses a pre-trained transformer-based model (`google/pegasus-large`) to fine-tune and generate abstractive summaries.
   - It includes training, evaluation, and fine-tuning of the model using a dataset like `allenai/scitldr`.

## Features:
- Extractive summarization using Word Frequency and TF-IDF methods.
- Abstractive summarization using a transformer model.
- Evaluation of summaries using ROUGE and BLEU scores.
- Fine-tuning pre-trained models for better performance on specific datasets.

## Evaluation Metrics:
- **ROUGE** (Recall-Oriented Understudy for Gisting Evaluation)
- **BLEU** (Bilingual Evaluation Understudy)

