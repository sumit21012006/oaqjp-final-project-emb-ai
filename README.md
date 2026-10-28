# Emotion Detection Application

This is an AI-based web application developed using Python, Flask, and Watson NLP for emotion detection. The application analyzes user input text and detects five key emotions: anger, disgust, fear, joy, and sadness, identifying the dominant emotion with its corresponding score.

## Features
- **Watson NLP Integration**: Processes text using IBM Watson NLP Emotion Predict model.
- **Emotion Analysis**: Accurately computes confidence scores for anger, disgust, fear, joy, and sadness.
- **Dominant Emotion Detection**: Identifies the primary emotion conveyed in the provided text.
- **Flask Web Deployment**: Interactive and user-friendly web interface served on localhost:5000.
- **Error Handling**: Graceful error handling for blank, invalid, or empty input queries.
- **Unit Testing**: Comprehensive test suite using Python `unittest` framework.
- **Static Code Analysis**: 10/10 rating adhering strictly to PEP8 standards using `pylint`.

## Project Structure
```
final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Setup & Running the Application
1. Install dependencies:
   ```bash
   pip install flask requests pylint
   ```
2. Run unit tests:
   ```bash
   python test_emotion_detection.py
   ```
3. Run static code analysis:
   ```bash
   pylint server.py
   ```
4. Start the Flask application:
   ```bash
   python server.py
   ```
5. Access the application in your browser at `http://localhost:5000`.
