# Character-Based-N-Gram-Language-Identification
A clean and modular implementation of character-level 2-gram and 3-gram statistical language models for language identification, including preprocessing, corpus statistics, model training, cross-validation, performance evaluation, and statistical significance testing.

This project demonstrates how character-based n-gram models can distinguish between two languages based solely on text structure, without requiring word-level tokenization or linguistic resources.
🔍 Features

Character-based 2-gram and 3-gram language models

Laplace (add-1) smoothing implementation

Automatic corpus loading and preprocessing (TXT, PDF, DOCX)

Sentence segmentation & basic text normalization

Model training using NLTK

10-fold cross-validation

Evaluation using:

Accuracy

Precision

Recall

F1-score

Paired t-test for 2-gram vs 3-gram statistical comparison

OOV sentence testing

Modular and easy-to-extend codebase
