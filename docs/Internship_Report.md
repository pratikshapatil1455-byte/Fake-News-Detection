# Internship Project Report
## Fake News Detection 

### Introduction
The project develops a machine-learning based NLP system for preliminary classification of news text.

### Problem Statement
To analyze news content and classify it as likely fake or likely real using text features and machine-learning algorithms.

### Objectives
1. Data collection and preparation
2. Exploratory data analysis
3. NLP preprocessing
4. TF-IDF feature extraction
5. Model training and comparison
6. Performance evaluation
7. Error analysis
8. Model saving and prediction

### Dataset
WELFake dataset. See `docs/DATASET_SOURCE.md` for source and dataset details.

### Methodology
Dataset → Cleaning → EDA → NLP → TF-IDF → Train/Test Split → Model Comparison → Evaluation → Error Analysis → Model Saving → Prediction.

### Algorithms
Logistic Regression, Multinomial Naive Bayes and Linear SVM.

### Results
After running the notebook, copy the actual values from `results/metrics.json` here. Never write an unverified accuracy.

### Conclusion
The project demonstrates an end-to-end NLP and machine-learning workflow for preliminary fake-news text classification.

### Future Scope
Transformer models, multilingual support, source credibility analysis, explainable AI and real-time verification.

### Limitations
The classifier learns patterns from the training dataset and cannot independently verify real-world claims.
