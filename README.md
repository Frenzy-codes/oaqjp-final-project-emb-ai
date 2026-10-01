# oaqjp-final-project-emb-ai

## Final Project: AI-Based Emotion Detector

This project is an AI-based web application that detects emotions in text using the Watson NLP library. It is built with Python and Flask, and analyzes text for five emotions: **anger**, **disgust**, **fear**, **joy**, and **sadness**, returning the dominant emotion.

### Features
- Emotion detection using Watson NLP Embeddable AI
- Web interface for real-time text analysis
- RESTful API endpoint for emotion prediction
- Error handling for invalid/blank inputs
- Unit tested with Python unittest framework
- Static code analysis with Pylint (10/10 score)

### Project Structure
```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
├── README.md
└── requirements.txt
```

### How to Run
1. Install dependencies: `pip install flask requests pylint`
2. Start the server: `python3 server.py`
3. Open your browser and navigate to `http://localhost:5000`

### Technologies Used
- Python 3
- Flask
- Watson NLP (Embeddable AI)
- HTML/CSS/JavaScript
- Pylint
