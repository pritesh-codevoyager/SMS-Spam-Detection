# 📱 SMS Spam Detection using Machine Learning

<div align="center">

### 🚀 Intelligent SMS Classification using Natural Language Processing & Machine Learning

**Python • Machine Learning • NLP • Scikit-Learn • Pandas • NumPy**

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge\&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-orange?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-Classification-red?style=for-the-badge)

</div>

---

# 📌 Project Overview

Spam messages have become a significant challenge in digital communication, leading to security risks, phishing attacks, and user inconvenience.

This project presents an intelligent SMS Spam Detection System that leverages Natural Language Processing (NLP) and Machine Learning algorithms to automatically classify incoming messages as **Spam** or **Ham (Legitimate Messages)**.

The solution transforms raw text messages into meaningful numerical features and applies machine learning techniques to achieve accurate and reliable spam detection.

---

# 🎯 Problem Statement

With the rapid growth of mobile communication, users receive thousands of unwanted promotional and fraudulent messages every day.

Traditional filtering methods struggle to detect evolving spam patterns.

The objective of this project is to:

✅ Automatically identify spam messages

✅ Reduce unwanted SMS communication

✅ Improve user security and privacy

✅ Enhance message filtering accuracy

✅ Support real-time spam classification

---

# 🏗️ Project Workflow

## 1️⃣ Data Collection

Collected SMS messages containing:

* Spam Messages
* Legitimate (Ham) Messages

### Dataset Features

| Feature | Description      |
| ------- | ---------------- |
| Label   | Spam / Ham       |
| Message | SMS Text Content |

---

## 2️⃣ Data Preprocessing

The text data was cleaned and standardized before model training.

### Preprocessing Techniques

✔ Lowercase Conversion

✔ Removal of Punctuation

✔ Removal of Special Characters

✔ Tokenization

✔ Stop Word Removal

✔ Stemming

✔ Text Normalization

---

## 3️⃣ Feature Engineering

Text messages were transformed into machine-readable numerical vectors using:

### Techniques Used

* Bag of Words (BoW)
* Count Vectorization
* TF-IDF Vectorization

---

## 4️⃣ Model Building

Multiple machine learning algorithms were evaluated to identify the best-performing model.

### Algorithms Tested

* Naive Bayes
* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## 5️⃣ Model Evaluation

Performance was measured using standard classification metrics.

### Evaluation Metrics

📊 Accuracy

📈 Precision

📉 Recall

🎯 F1 Score

📋 Confusion Matrix

---

# 📊 System Architecture

```text
SMS Message
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Extraction (TF-IDF)
      │
      ▼
Machine Learning Model
      │
      ▼
Spam / Ham Prediction
```

---

# 📈 Key Features

### Intelligent Classification

Automatically predicts whether a message is Spam or Ham.

### NLP-Based Processing

Extracts meaningful information from text messages.

### High Accuracy

Machine learning algorithms provide reliable predictions.

### User-Friendly Interface

Simple interface for message classification.

### Real-Time Prediction

Instant spam detection capability.

---

# 🛠️ Technology Stack

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Scikit-Learn
* NLTK
* Matplotlib
* Seaborn

## Machine Learning Techniques

* Supervised Learning
* Text Classification
* Natural Language Processing (NLP)
* Feature Engineering

---

# 📂 Project Structure

```text
SMS-Spam-Detection/
│
├── dataset/
│   └── spam.csv
│
├── models/
│   └── spam_classifier.pkl
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   ├── prediction.py
│
├── app/
│   └── app.py
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Exploratory Data Analysis (EDA)

Analysis performed on:

### Message Distribution

* Spam Count
* Ham Count

### Word Frequency Analysis

* Most Common Spam Words
* Most Common Ham Words

### Message Length Analysis

* Average Spam Message Length
* Average Ham Message Length

### Visualization

* Bar Charts
* Histograms
* Word Clouds
* Frequency Plots

---

# 🎯 Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 98%+  |
| Precision | High  |
| Recall    | High  |
| F1 Score  | High  |

*(Actual results may vary depending on dataset and model selection.)*

---

# 🚀 How to Run

## Clone Repository

```bash
git clone https://github.com/yourusername/SMS-Spam-Detection.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python app.py
```

---

# 💡 Business Benefits

### Security Enhancement

Protects users from fraudulent and phishing messages.

### Improved User Experience

Reduces unwanted SMS interruptions.

### Automated Filtering

Minimizes manual effort in spam identification.

### Scalable Solution

Can be integrated into messaging platforms and mobile applications.

---

# 🎯 Skills Demonstrated

✅ Python Programming

✅ Machine Learning

✅ Natural Language Processing (NLP)

✅ Text Classification

✅ Feature Engineering

✅ Data Cleaning

✅ Model Evaluation

✅ Exploratory Data Analysis

✅ Scikit-Learn

---

# 🔮 Future Enhancements

🚀 Deep Learning Models (LSTM)

🚀 Transformer-Based Models (BERT)

🚀 Multi-Language Spam Detection

🚀 Real-Time API Deployment

🚀 Cloud Integration

🚀 Mobile Application Deployment

---

# 👨‍💻 Author

## Pritesh Raj

**Aspiring Data Analyst | Machine Learning Enthusiast | Python Developer**

### Skills

Python • SQL • Power BI • Machine Learning • NLP • Pandas • NumPy • Data Analytics

---

# ⭐ Support

If you found this project useful:

⭐ Star this Repository

🍴 Fork the Project

🤝 Contribute & Collaborate

📢 Share Feedback

---

### "Leveraging Machine Learning to Make Digital Communication Safer and Smarter."
