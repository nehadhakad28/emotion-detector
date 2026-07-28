# Emotion Detector

## Project Overview

Emotion Detector is an AI-powered web application that detects emotions from user-provided text using the IBM Watson NLP library. The application analyzes the input text and identifies the dominant emotion along with emotion scores.

This project was developed as part of the IBM Skills Network final project for the course on developing AI-powered applications.

## Features

- Detects emotions from text input
- Returns emotion scores for:
  - Anger
  - Disgust
  - Fear
  - Joy
  - Sadness
- Identifies the dominant emotion
- REST API implemented using Flask
- Error handling for invalid or empty input
- Unit tests included
- Static code analysis using Pylint

## Technologies Used

- Python 3
- Flask
- IBM Watson NLP Library
- Requests
- Pytest / Unittest
- Pylint

## Project Structure

```
emotion-detector/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── server.py
├── test_emotion_detection.py
├── requirements.txt
├── README.md
└── LICENSE
```

## Installation

Clone the repository.

```bash
git clone https://github.com/<your-github-username>/oaqjp-final-project-emb-ai.git
```

Move into the project directory.

```bash
cd oaqjp-final-project-emb-ai
```

Install the required packages.

```bash
pip install -r requirements.txt
```

## Running the Application

Start the Flask server.

```bash
python server.py
```

Open your browser and visit:

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

## Expected Output

The application returns emotion scores similar to:

```json
{
  "anger": 0.01,
  "disgust": 0.00,
  "fear": 0.02,
  "joy": 0.94,
  "sadness": 0.03,
  "dominant_emotion": "joy"
}
```

## Author

Developed by Neha Dhakad as part of the IBM Skills Network Final Project.
