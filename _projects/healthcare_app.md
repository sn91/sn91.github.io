---
layout: page
title: Android App for Healthcare
description: Gamified therapy assistant with sentiment analysis for Pepper robot
img: 
importance: 2
category: Major
---

## Project Overview

Built a **gamified Android application** (Java/Kotlin) for the Pepper robot to assist in depression therapy. The app combines **real-time sentiment analysis** and **facial recognition** to monitor patient engagement and mood.

**Duration**: April 2023 – August 2023  
**Institution**: TU Clausthal

## Key Features

### Real-time Sentiment Analysis
- Implemented NLP-based mood detection from patient text input
- Used **TF-IDF** for feature extraction and **SVM** classifiers for sentiment classification
- Enabled therapists to track patient emotional states over sessions

### Facial Recognition & Engagement Monitoring
- Integrated **OpenCV** and **MediaPipe** for face detection and tracking
- Used pre-trained **CNN models** for emotion recognition from facial expressions
- Monitored patient engagement levels during therapy sessions

### Gamification Elements
- Designed interactive activities to encourage patient participation
- Progress tracking and reward systems to maintain engagement
- Adaptive difficulty based on patient responses

## Technical Stack

- **Mobile Development**: Java, Kotlin, Android SDK
- **Computer Vision**: OpenCV, MediaPipe
- **Machine Learning**: TF-IDF, SVM, CNN
- **Robot Integration**: Pepper SDK
- **Backend**: Python

## Architecture

```
┌─────────────────┐     ┌─────────────────┐
│   Pepper Robot  │────▶│  Android App    │
└─────────────────┘     └────────┬────────┘
                                 │
         ┌───────────────────────┼───────────────────────┐
         ▼                       ▼                       ▼
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│ Text Sentiment  │     │ Facial Emotion  │     │   Gamification  │
│    Analysis     │     │   Recognition   │     │     Engine      │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

## Impact

- Provided therapists with objective data on patient emotional states
- Increased patient engagement through interactive gamified activities
- Enabled remote monitoring of therapy session effectiveness

