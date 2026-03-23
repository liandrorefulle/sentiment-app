# Sentiment Analyzer

A web app that analyzes whether a text input is positive, negative, or neutral using NLP.

## Built With
- Python, Flask, TextBlob, HTML/CSS

## How to Run

1. Clone the repository
   git clone https://github.com/liandrorefulle/sentiment-app.git
   cd sentiment-app

2. Create and activate a virtual environment
   python -m venv venv
   venv\Scripts\activate

3. Install dependencies
   pip install flask textblob nltk

4. Download NLP data
   python -c "import nltk; nltk.download('punkt'); nltk.download('averaged_perceptron_tagger')"

5. Run the app
   python app.py

6. Open browser and go to http://127.0.0.1:5000
```
