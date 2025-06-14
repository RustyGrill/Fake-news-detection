# Fake-news-detection
A Machine learning approach to fake news detection and classification

## 📋 Overview

This project focuses on the detection and classification of fake news using traditional machine learning techniques. By applying Logistic Regression and Random Forest models, we aim to accurately distinguish between real and fake news articles based on their textual content.

The repository includes data preprocessing, model training, evaluation, and comparison of performance metrics. The goal is to demonstrate that even classical machine learning models can effectively address the problem of fake news classification when paired with proper feature engineering.

## ✅ Features

* Clean and modular Python implementation

* Data preprocessing and vectorization (Count vectorization)

* Implementation of Logistic Regression and Random Forest

* Performance evaluation using accuracy, precision, recall, and F1-score

## 🔄 Workflow
1. Dataset Collection\
Acquired a labeled dataset containing real and fake news articles.


2. Data Preprocessing\
Removed null entries, punctuation, and stopwords.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tokenized and cleaned the news content for further analysis.

3. Feature Extraction\
Used Count Vectorization to convert text into numerical feature vectors.

4. Model Building\
Trained two classifiers:

* Logistic Regression

* Random Forest

  &nbsp;&nbsp;Used Scikit-learn for implementation.

5. Model Evaluation\
Evaluated both models using:

  - Accuracy

  - Precision

  - Recall

  - F1-Score

  &nbsp;&nbsp;Performed 5-fold cross-validation for robustness.

6. Results and Comparison\
Both models achieved high accuracy, confirming the effectiveness of traditional ML techniques for text classification.

  &nbsp;&nbsp;Logistic Regression showed faster training time, while Random Forest provided better interpretability in terms of feature importance.

 ## 📊 Results

Here is a sample result of the model performance:

<h2>Accuracy and precison using Logistic regression</h2>
<img src="images/WhatsApp Image 2025-05-27 at 00.14.39_fe632eb2.jpg" alt="Model Results" width="600"/>

<h2>Confusion matrix using Logistic regression</h2>
<img src="images/WhatsApp Image 2025-05-27 at 00.14.54_0904be53.jpg" alt="Model Results" width="600"/>

<h2>Accuracy and precison using Random_forest</h2>
<img src="images/WhatsApp Image 2025-05-27 at 00.48.03_82257f07.jpg" alt="Model Results" width="600"/>

<h2>Confusion matrix using Random_forest</h2>
<img src="images/WhatsApp Image 2025-05-27 at 00.27.07_a24bca4d.jpg" alt="Model Results" width="600"/>


## 🚀 Future Improvements
* Use of More Advanced Text Representations
  Word2Vec, GloVe, or FastText for capturing semantic relationships.
  TF-IDF Vectorization to weigh more informative terms.
  
*  Incorporating NLP Preprocessing
  for example: Lemmatization/Stemming, Named Entity Recognition (NER).
   
*  Handling Imbalanced Datasets
   Using SMOTE or ADASYN for oversampling
   Applying class weighting in models
   
*  Real-Time Fake News Detection
   Deploying the models as a web service using Flask/Django, Streamlit, etc.



  



