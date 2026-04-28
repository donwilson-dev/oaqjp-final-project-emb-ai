# Final Project: Emotion Detector

## 📌 Overview

This project implements an AI-based Emotion Detection application using the Watson NLP library.
It analyzes user-provided text and returns the detected emotions along with their corresponding scores.

---

## 🚀 Features

* Emotion detection using Watson NLP
* REST API integration
* Flask-based web interface
* Structured JSON output
* Error handling for invalid and empty input
* Unit testing for validation
* PEP8-compliant code (pylint 10/10)

---

## 🛠️ Technologies Used

* Python
* Flask
* Watson NLP (embedded libraries)
* Requests
* Unittest
* Pylint

---

## 📂 Project Structure

```
EmotionDetection/
│── __init__.py
│── emotion_detection.py

templates/
static/

server.py
test_emotion_detection.py
README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/donwilson-dev/oaqjp-final-project-emb-ai.git
cd oaqjp-final-project-emb-ai
```

### 2. Install dependencies

```bash
pip install requests flask
```

### 3. Run the application

```bash
python3 server.py
```

---

## 🌐 Usage

Open your browser and go to:

```
http://localhost:5000
```

Enter text to analyze emotions.

---

## 🧪 Running Tests

```bash
python3 -m unittest test_emotion_detection
```

---

## ⚠️ Error Handling

* Empty input → "No input provided"
* Invalid/unsupported text → "Invalid input"

---

## 📊 Example Output

```
Emotion: joy
Score: 0.85
```

---

## ✅ Static Code Analysis

Pylint score:

```
10.00/10
```

---

## 👤 Author

Don Wilson
