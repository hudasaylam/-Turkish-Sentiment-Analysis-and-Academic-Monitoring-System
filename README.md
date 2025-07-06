# -Turkish-Sentiment-Analysis-and-Academic-Monitoring-System

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
- **Labels:** 3 classes (Positive, Neutral, Negative)
- **All training, testing, and inference adapted for Turkish**
## Model Download

## Model
The pre-trained BERT model and tokenizer files are too large for GitHub.

You can download all required files from Hugging Face:

👉 [Goemotions_data_turkish_sentiment_anaysis - HUDASAYLAM on Hugging Face](https://huggingface.co/HUDASAYLAM/Goemotions_data_turkish_sentiment_anaysis/tree/main)

After downloading, please place the files inside the `Flask/model_files/` directory.

**Note:**  
If you are only running the demo and not training, you do not need any additional files.

## Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/turkish-sentiment-academic-tracking-system.git
   cd turkish-sentiment-academic-tracking-system
