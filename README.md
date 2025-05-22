# 🌐 Language Detection Web App

This project is a simple web application that detects the language of a given text input using a **Multinomial Naive Bayes** classifier. The application is built using **Flask** for the backend, **HTML/CSS** for the frontend, and **scikit-learn** for model training and prediction.

---

## 📌 Features

- Detects language from user input text
- Pretrained on multilingual dataset (`Language_Detection.csv`)
- Built with a simple and responsive user interface
- Uses machine learning (Naive Bayes) for prediction

---

## 🧠 How It Works

1. **Text Preprocessing**:
   - Clean the text by removing special characters and converting to lowercase.

2. **Feature Extraction**:
   - Convert text into numerical features using `CountVectorizer`.

3. **Label Encoding**:
   - Convert language labels into integers using `LabelEncoder`.

4. **Model Training**:
   - Train a **Multinomial Naive Bayes** classifier on the dataset.

5. **Prediction**:
   - User input is transformed and predicted using the trained model.

---

## 🛠️ Tech Stack

- **Backend**: Flask
- **Frontend**: HTML, CSS
- **Machine Learning**: scikit-learn
- **Data Handling**: pandas, numpy


