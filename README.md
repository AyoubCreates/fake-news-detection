# Fake News Detection – Multi-Class Classification

## Project Overview
Developed a BERT-based multi-class text classification model to detect fake news statements across six categories:
- true
- mostly-true
- half-true
- barely-true
- false
- pants-fire

Implemented data preprocessing, tokenization, and fine-tuning using PyTorch and HuggingFace Transformers.

## Dataset
- Train, Validation, Test splits
- Features: statement text, label
- Dataset visualizations included (label distribution, sentence lengths)

## Model
- BERT-base-uncased (Transformer)
- Fine-tuning with AdamW optimizer
- Batch size: 16
- Training epochs: 2 (baseline experiment)

## Results
- Test set accuracy: 26%  
*Note: Low accuracy due to limited epochs; this is baseline performance.*

## Technologies
Python, PyTorch, HuggingFace Transformers, BERT, NLP, Data Visualization

## Author
Ayoub Ben-Yamina
