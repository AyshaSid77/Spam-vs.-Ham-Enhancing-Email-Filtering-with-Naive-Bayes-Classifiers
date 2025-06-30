# Email Spam vs Ham Classification Using Naive Bayes

## Overview

This project implements machine learning models to classify emails as either **spam** (unsolicited bulk emails) or **ham** (legitimate emails). Using datasets containing easy ham, hard ham, and spam emails, we compare the performance of two popular Naive Bayes classifiers Multinomial and Bernoulli  to evaluate their effectiveness in email classification.

## Dataset

- **Easy Ham:** Shorter, straightforward legitimate emails that are easier to distinguish from spam.
- **Hard Ham:** Legitimate emails that contain spam-like features such as links and similar wording, making classification more challenging.
- **Spam:** Unwanted bulk emails, often containing HTML content, links, and common spam keywords.

## Features

- Data labeling and splitting into training and test sets.
- Text preprocessing using `CountVectorizer` for tokenization and feature extraction.
- Training of Multinomial and Bernoulli Naive Bayes classifiers.
- Evaluation metrics including accuracy, precision, recall, and confusion matrix.
- Visualizations of classifier performance.

## Results Summary

- Multinomial Naive Bayes consistently outperforms Bernoulli Naive Bayes, especially on the easy ham dataset.
- Hard ham emails are more difficult to classify accurately due to their similarity to spam.
- Bernoulli Naive Bayes tends to produce more false positives compared to Multinomial.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: `scikit-learn`, `pandas`, `matplotlib`

### Installation

```bash
pip install -r requirements.txt
