# Emotion-DetectAI

> An AI-powered Flask web application that detects emotions from user-provided text using natural language processing.

## 🌟 Overview

**Emotion-DetectAI** analyzes user input and predicts the underlying emotion—such as joy, sadness, anger, or fear—using AI models and vector similarity techniques. Built as part of the OAQJP Embedded AI course, this project showcases how NLP and lightweight web apps can work together for real-time emotional intelligence.

## 🚀 Features

* 🔍 Emotion detection from text
* 🧠 Embedding-based semantic understanding
* 🖥️ Simple Flask-based web interface
* 🧪 Unit-tested emotion classification
* 🧱 Modular and extensible Python structure

## 🛠️ Technologies Used

* Python 3.x
* Flask
* scikit-learn
* NumPy
* `sentence-transformers` (for vector embeddings)
* HTML/CSS/JS for the front end

## 📁 Project Structure

```
Emotion-DetectAI/
├── EmotionDetection/         # Core emotion detection logic
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/                # HTML templates for web interface
│   └── index.html
├── static/                   # CSS and JS files
│   ├── style.css
│   └── script.js
├── test_emotion_detection.py # Unit tests
├── server.py                 # Flask app
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Daksh-Aggarwal/Emotion-DetectAI.git
cd Emotion-DetectAI
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
python server.py
```

Then open [http://localhost:5000](http://localhost:5000) in your browser.

## 🧪 Running Tests

Run the built-in test file to ensure everything is working:

```bash
pytest test_emotion_detection.py
```

## 💡 Example Usage

**Input:**

```
I just got into my dream college!
```

**Detected Emotion:**

```
Joy 😄
```

## 📌 Future Improvements

* 🎤 Voice-to-text support
* 🌍 Multi-language detection
* 📊 Confidence scores visualization
* 📱 Mobile-responsive UI

## 🡩‍💻 Author

Made with ❤️ by **Daksh Aggarwal**
[GitHub](https://github.com/Daksh-Aggarwal) • [LinkedIn](https://www.linkedin.com/in/dakshaggarwal7)

## 📄 License

This project is licensed under the MIT License.
