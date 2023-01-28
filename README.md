# SemEval-2023-Task-6-classifying-Legal-Documents-based-on-their-respective-rhetorical-roles
SemEval-2023-Task-6 (https://sites.google.com/view/legaleval/home): Considered the task of classifying sentences in Legal Documents based on their respective rhetorical roles and obtained a precision on validation dataset of 81.6% in the final approach (Baseline modified with T5-large tokenizer and encoder).

# Experiment details

Tried all kinds of approaches ranging from Naive Bayes, Information Retrieval, LSTMs Large Language Model Embedding.  Baseline modified with large language model embedding (T5) outperformed the baseline results.

The folders individually contain information about how to execute each model in their respective Readme files.

The models are described below in brief:
1. Naive Bayes
2. Doc2Vec
3. Wiki BM25 Lexical Model + Logistic Regression
4. Glove Embedding + Fully Connected Layer
5. Glove Embedding + 1 Dimensional CNN
6. T5 Encoder + FAISS (Facebook AI Similarity Search)
7. T5 Encoder + PLDA (Probabilistic Linear Discriminant Analysis)
8. T5-base + LSTM
9. BaseLine
10. Our Approach (Best) - Baseline modified with T5-large tokenizer and encoder
11. Sentence Transformer (paraphrase-xlm-r-multilingual-v1)+ PLDA
12. Sentence Transformer (paraphrase-xlm-r-multilingual-v1)+ FAISS
13. Baseline modified with T5-base encoder + BiLSTM with 1024 hidden layer
14. T5-base encoder + BiLSTM with three hidden layer
15. Baseline modified with LegalBert
16. Baseline modified with LegalBert-large-1.7m-1

Also ran the baseline and the baseline output can be found in baseline_output.txt
Baseline github link: https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline

Datasets is in datasets folder.
