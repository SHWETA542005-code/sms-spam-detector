# 📩 SMS/Email Spam Classifier

A machine learning web application that classifies SMS/Email messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques.

The model is built using TF-IDF vectorization and Multinomial Naive Bayes, and deployed using Streamlit.

---

## 🚀 Live Demo
https://sms-spam-detector-tzfd.onrender.com

---

## 🧠 Project Overview

Spam detection is a classic NLP classification problem.  
This project implements a complete end-to-end pipeline:

1. Text preprocessing
2. Feature extraction using TF-IDF
3. Model training using Multinomial Naive Bayes
4. Deployment with Streamlit

---

## 🔍 Features

- Text cleaning (lowercasing, tokenization, stopword removal, stemming)
- TF-IDF Vectorization
- Multinomial Naive Bayes classification
- Interactive web interface using Streamlit
- Real-time prediction

---

## 🛠 Tech Stack

- Python
- NLTK
- Scikit-learn
- Streamlit
- Render (Deployment)

---

## ⚙️ How It Works

1. User enters a message.
2. The message is preprocessed:
   - Converted to lowercase
   - Tokenized
   - Stopwords removed
   - Stemming applied
3. The cleaned text is transformed using a pre-trained TF-IDF vectorizer.
4. The trained Naive Bayes model predicts whether the message is spam or not.

---

## 📊 Model Details

- Vectorizer: TF-IDF
- Algorithm: Multinomial Naive Bayes
- Evaluation Metrics: Accuracy, Precision, Recall

---

## 📁 Project Structure
sms-spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md

---

## 📌 Future Improvements

- Add model confidence score display
- Improve preprocessing pipeline
- Compare with Logistic Regression
- Deploy with Docker for production readiness

---

## 👩‍💻 Author

Shweta  
