# Internship PPT —  Fake News Detection 

## Slide 1 — Title
 Fake News Detection 
Internship Project
B.Tech Data Science

## Slide 2 — Introduction
- Rapid growth of digital news and social media
- Misleading information can spread quickly
- Manual verification is time-consuming
- NLP and ML can assist with preliminary classification

## Slide 3 — Problem Statement
Develop an NLP-based system that analyzes news text and predicts whether it is likely fake or likely real.

## Slide 4 — Objectives
- Prepare a large labeled dataset
- Perform EDA and cleaning
- Apply NLP preprocessing
- Extract TF-IDF features
- Train and compare ML models
- Evaluate and save the selected model
- Provide interactive prediction

## Slide 5 — Dataset
WELFake dataset
- 72,134 accessible articles
- 35,028 real
- 37,106 fake
- Title, Text, Label
- 0 = Fake, 1 = Real
- Source: Zenodo

## Slide 6 — System Architecture
Dataset → Cleaning → NLP → TF-IDF → ML Models → Evaluation → Best Model → Prediction

## Slide 7 — NLP & Feature Engineering
- Lowercasing
- URL/HTML removal
- Noise and punctuation removal
- Whitespace normalization
- TF-IDF unigrams and bigrams

## Slide 8 — Machine Learning
- Logistic Regression
- Multinomial Naive Bayes
- Linear SVM
- Model selected using measured F1-score

## Slide 9 — Results
Insert actual notebook outputs:
- Model comparison chart
- Confusion matrix
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

**Do not invent metrics. Copy them from `results/metrics.json`.**

## Slide 10 — Conclusion
- Complete NLP/ML pipeline implemented
- Model comparison and error analysis performed
- Saved model supports new-text prediction

## Slide 11 — Future Scope & Limitations
Future: transformers, multilingual NLP, source credibility, explainable AI, real-time verification.
Limitation: model predictions depend on dataset patterns and are not independent fact checks.

## Slide 12 — Thank You
Thank You
