# oaqjp-final-project-emb-ai

## Emotion Detector

An AI-based web application that detects emotions in text using the Watson NLP Embedded AI library.

## Project Structure

```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Tasks Completed

- **Task 1**: Repository setup
- **Task 2**: Emotion detection using Watson NLP library
- **Task 3**: Formatted output with dominant emotion
- **Task 4**: Packaged as `EmotionDetection` module
- **Task 5**: Unit tests for all 5 emotions
- **Task 6**: Flask web deployment
- **Task 7**: Error handling for blank/invalid input
- **Task 8**: Static code analysis with pylint (10/10)

## Running the Application

```bash
pip install flask requests
python server.py
```

Open http://localhost:5000 in your browser.

## Running Tests

```bash
python -m pytest test_emotion_detection.py -v
```

## Static Code Analysis

```bash
pylint server.py
```
