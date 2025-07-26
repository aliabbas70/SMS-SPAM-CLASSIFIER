# 📱 SMS Spam Classifier

A simple machine learning web app built with **Streamlit** that classifies SMS messages as **Spam** or **Ham (Not Spam)**.

This project uses **Natural Language Processing (NLP)** and a **Naive Bayes classifier**, trained on text message data. The app allows users to input an SMS message and get instant prediction results.

---

## 🌐 Live Demo

👉 [Click here to try the app](https://huggingface.co/spaces/aliabbas70/SMS-SPAM-CLASSIFIER)

---

## 🧠 Features

- Predicts whether a message is spam or not
- Built using Scikit-learn, NLTK, and Streamlit
- Uses TF-IDF vectorization for text processing
- Simple, clean interface

---

## 📁 Files

| File Name       | Description                        |
|----------------|------------------------------------|
| `app.py`        | Streamlit web app source code      |
| `model.pkl`     | Trained Naive Bayes model          |
| `vectorizer.pkl`| TF-IDF vectorizer used for NLP     |
| `requirements.txt` | Python dependencies              |

---

## 🚀 How to Run the App Locally

1. **Clone the repo:**

```bash
git clone https://github.com/aliabbas70/sms-spam-classifier.git
cd sms-spam-classifier
