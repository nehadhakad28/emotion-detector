# Emotion Detector

## Project Name

Emotion Detector

## Description

Emotion Detector is an AI-powered web application developed using the IBM Watson NLP library. It analyzes text entered by a user and detects the emotions expressed in the text. The application returns emotion scores for anger, disgust, fear, joy, and sadness, along with the dominant emotion.

This project was completed as part of the IBM Skills Network Final Project.

## Features

- Detect emotions from user-provided text
- Returns scores for:
  - Anger
  - Disgust
  - Fear
  - Joy
  - Sadness
- Identifies the dominant emotion
- Flask-based web interface
- Handles invalid and empty input gracefully
- Includes unit tests
- Static code analysis with Pylint

## Technologies Used

- Python
- Flask
- IBM Watson NLP
- HTML
- CSS
- JavaScript
- Pylint
- Unittest

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-github-username>/emotion-detector.git
```

Move to the project directory:

```bash
cd emotion-detector
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

```bash
python server.py
```

Then open your browser and visit:

```
http://localhost:5000
```

## Running Unit Tests

```bash
python -m unittest test_emotion_detection.py
```

## Running Static Code Analysis

```bash
pylint EmotionDetection
```

## Author

Neha Dhakad
