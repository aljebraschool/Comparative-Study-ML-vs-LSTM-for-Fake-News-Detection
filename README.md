# Fake News Detection: Traditional ML vs. LSTM Models
Fake New Detection Model using Ml and LSTM

Welcome to the Fake News Detection project repository. This project aims to compare the performance of traditional machine learning models with a Long Short-Term Memory (LSTM) model in identifying and differentiating between real and fake news articles. 

## Overview

The exponential growth of information dissemination via social media platforms has not only amplified the accessibility of information but has also escalated the prevalence of unverified news. The proliferation of fake news poses a significant threat not only to the safety of individual consumers but also to the overall safety of the public. The sheer volume of such content on these platforms makes it exceedingly difficult to manually discern between authentic and counterfeit news.

## Data Collection

Fake news refers to information deliberately created or distorted to appear as genuine news, often with the intention of misleading the public. The automated detection of fake news involves verifying the accuracy of statements represented as news. Numerous datasets, containing both authentic and fabricated news articles, are available online. However, for the purposes of this research, a fake news dataset sourced from Kaggle will be utilized. This dataset consists of two files: the training dataset, comprising 20,386 articles, and a test dataset, consisting of 5,126 articles, which will be used to assess the model's performance. It encompasses news articles across a multitude of subjects, including entertainment, crime, and sports, rather than being limited to politics. The dataset is structured with five columns: ID, title, author, text, and label.

## Results

The performance of the models is summarized as follows:

- Logistic Regression achieved an accuracy of 95.5% with 87 false positives and 121 false negatives.
- Support Vector Machine achieved an accuracy of 96.8% with 71 false positives and 76 false negatives.
- Naive Bayes achieved an accuracy of 73.4% with 3 false positives and 1215 false negatives.
- Decision Tree achieved an accuracy of 88.5% with 259 false positives and 265 false negatives.
- Long Short-Term Memory achieved an accuracy of 92.1% with 254 false positives and 105 false negatives.

## Conclusion

Based on the performance metrics, the Support Vector Machine model emerged as the top performer in terms of accuracy and false positives. However, the LSTM model also demonstrated promising results and could potentially be further optimized for better performance. The project provides insights into the effectiveness of traditional machine learning and deep learning approaches in the context of fake news detection.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


