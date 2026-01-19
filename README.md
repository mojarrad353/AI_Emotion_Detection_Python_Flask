# 🧠 AI Emotion Detection Web Application

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![Testing](https://img.shields.io/badge/Testing-unittest-success)

---

## 📌 Overview

The **Emotion Detection Web Application** is a Python-based project that analyzes user-provided text and identifies the underlying emotions using **Natural Language Processing (NLP)**.

Built with **Flask**, the application integrates an external **Watson NLP Emotion Prediction API** to classify emotions such as **anger, disgust, fear, joy, and sadness**, and automatically determines the **dominant emotion** based on the highest confidence score.

To ensure reliability and maintainability, the project includes **unit tests using Python’s `unittest` framework**.

---

## 🚀 Features

- 🔍 Emotion detection from raw text input  
- 🏆 Automatic identification of dominant emotion  
- 🌐 REST API integration using `requests`  
- ⚙️ Flask-based web service  
- 🛡️ Graceful handling of invalid or empty input  
- 🧪 Automated testing with `unittest`  
- 🧩 Clean, modular, and maintainable Python code  

---

## 😊 Supported Emotions

| Emotion | Description |
|-------|------------|
| 😠 Anger | Expression of frustration or rage |
| 🤢 Disgust | Feeling of revulsion |
| 😨 Fear | Sense of anxiety or threat |
| 😄 Joy | Happiness or delight |
| 😢 Sadness | Feeling of sorrow or loss |

**Dominant Emotion** is calculated as the emotion with the highest confidence score.

---

## 🛠️ Tech Stack

- **Language:** Python 3  
- **Framework:** Flask  
- **API Integration:** Requests  
- **Response Handling:** JSON  
- **Testing:** unittest  
- **NLP Service:** IBM Watson Emotion Prediction API  

---

## 📂 Project Structure

```text
EmotionDetection/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py     # Core emotion detection logic
│
├── static/
│   └── mywebscript.js            # Front-end JavaScript
│
├── templates/                    # HTML templates
│
├── server.py                     # Flask application entry point
├── test_emotion_detection.py     # Unit tests
├── README.md                     # Project documentation
├── LICENSE
└── .gitignore
```

## ⚙️ Installation & Usage
Clone the Repository: git clone https://github.com/mojarrad353/AI_Emotion_Detection_Python_Flask
