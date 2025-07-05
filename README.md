# -Turkish-Sentiment-Analysis-and-Academic-Monitoring-System
# Turkish Sentiment Analysis and Academic Tracking System

A web app for analyzing Turkish student emotions and academic performance.  
Trained on the Turkish-translated GoEmotions dataset, reduced to 4 sentiment classes.  
Includes BERT-based NLP and anomaly detection with a clean Flask UI.

## Features

- 🧠 Turkish sentiment analysis (4-class, GoEmotions-based, BERT model)
- 📈 Academic anomaly detection (Isolation Forest)
- 🔥 Simple Flask web interface
- 💬 Analyze both student texts and grades

## Data

- **Dataset:** GoEmotions (originally Google’s), auto-translated to Turkish
- **Labels:** 4 classes (Positive, Neutral, Negative)
- **All training, testing, and inference adapted for Turkish**

## Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/turkish-sentiment-academic-tracking-system.git
   cd turkish-sentiment-academic-tracking-system
