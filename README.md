# 📧 Spam Email Detector using Machine Learning

A machine learning-based desktop application that classifies messages as **Spam** or **Not Spam** using Natural Language Processing and a Naive Bayes classifier. The app features a clean and interactive GUI built with **Tkinter**.

---

## 🚀 Features

- ✅ Real-time spam classification
- 🧠 NLP preprocessing: cleaning, tokenization, stemming
- 🔢 CountVectorizer for converting text to numerical format
- 📊 Trained using the Multinomial Naive Bayes algorithm
- 💾 Model and vectorizer serialized using `pickle`
- 🖥️ Simple GUI using Tkinter

---

## 🧠 Technologies Used

- Python
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Tkinter
- Pickle

---

## 📁 Project Structure

spam-email-detector/
├── model.pkl # Trained model
├── vector.pkl # Trained CountVectorizer
├── email_spam.py # Main ML training and prediction logic
├── email_detector.py # detect spam or ham email GUI using Tkinter
├── spamemail.csv # Dataset used
├── spam.py # detect spam or gam SMS GUI TKINTER


---

## 📊 Dataset

This project uses the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) available on Kaggle. It contains 5,574 labeled SMS messages.

---
✅ Sample Output

Input: Congratulations! You have won a free iPhone. Claim now.
Output: ❌ This email is SPAM!

Input: Hey, are we still meeting tomorrow?
Output: ✅ This email is NOT spam.
























