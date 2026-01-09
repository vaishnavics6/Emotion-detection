🎭 Bimodal Emotion Detection System (Text & Audio)
📌 Project Overview

This project is a web-based Bimodal Emotion Detection System that analyzes human emotions using text input and audio signals. The system combines insights from both modalities to provide more accurate and meaningful emotion predictions.

The application is built using Flask and applies Natural Language Processing (NLP) techniques for text analysis along with audio-based heuristics for speech emotion detection.

🎯 Objectives

Detect emotions from user-entered text

Analyze emotions from audio files

Combine (fuse) text and audio predictions for better accuracy

Display detailed emotion probabilities and explanations

Log predictions for future analysis

🧠 Emotions Detected

The system identifies the following emotions:

Happiness

Sadness

Anger

Fear

Surprise

Loneliness

Disappointment

Frustration

Neutral

🛠️ Technologies Used

Programming Language: Python

Web Framework: Flask

Libraries:

text2emotion

NumPy

Librosa (optional – for audio processing)

Emoji

Frontend: HTML, CSS (Flask templates)

Logging: CSV-based logging system

⚙️ System Features

Text-based emotion analysis using enhanced emotion lexicons

Audio emotion detection using filename-based heuristics and signal analysis

Emotion probability calculation and confidence scoring

Emotion breakdown with human-readable explanations

CSV logging of all predictions

REST-style API endpoint for recent analysis results
