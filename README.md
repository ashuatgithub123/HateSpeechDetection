# HateSpeechDetection

An end-to-end project for classifying tweets into three categories: Hate Speech, Offensive, and Neither. This project demonstrates text preprocessing, feature extraction using TF-IDF, model training with Logistic Regression, and evaluation using accuracy metrics and classification reports.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)

---

## Overview
This project is designed to classify tweets based on their content. The workflow includes:
- **Data Preprocessing:** Cleaning tweets by removing URLs, mentions, hashtags, punctuation, numbers, and stopwords.
- **Feature Extraction:** Converting text data into TF-IDF features.
- **Model Training:** Using Logistic Regression to train on the processed dataset.
- **Evaluation:** Generating accuracy scores and a detailed classification report.

---

## Features
- **Data Cleaning:** Custom function to preprocess and clean raw tweet text.
- **TF-IDF Vectorization:** Extracts numerical features from cleaned text.
- **Stratified Splitting:** Ensures balanced training and testing datasets.
- **Model Evaluation:** Provides both overall accuracy and a classification report with precision, recall, and F1-scores.

---
