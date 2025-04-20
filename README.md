# Hate Speech Detection using NLP and Machine Learning

This project focuses on identifying **hate speech** within a given dataset using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to build an automated system that classifies text into one of the following categories:

- **Hate Speech**
- **Offensive Language**
- **No Hate or Offensive Language**

## 📊 Dataset

The dataset (`X`) contains labeled text data, typically sourced from social media platforms such as Twitter or online forums. Each entry includes:

- A text message
- A corresponding label indicating its classification

## 🧠 Project Pipeline

### 1. Data Preprocessing
- Cleaning text (removing URLs, mentions, hashtags, etc.)
- Tokenization
- Stopword removal
- Lemmatization or stemming

### 2. Feature Extraction
- TF-IDF Vectorization
- Word Embeddings (e.g., Word2Vec, GloVe, BERT)

### 3. Model Training
- Classical ML models: Logistic Regression, Naive Bayes, SVM
- Optionally: Deep learning models like LSTM, BERT-based classifiers

### 4. Model Evaluation
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 💡 Use Case

This system can be integrated into content moderation pipelines to automatically detect and flag harmful language in real-time. Applications include:

- Social media platforms
- Online forums and communities
- Comment sections on websites
- Messaging platforms

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sathwika-29/Hate_speech_detection_using_X_Data.git
   cd Hate_speech_detection_using_X_Data
