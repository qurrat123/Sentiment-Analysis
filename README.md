Twitter Sentiment Analysis

Overview
Classify Tweets (positive/negative) using TF-IDF features and ML models (Logistic Regression, SVM, Random Forest).

Requirements
• Python 3.7+
• pandas, numpy, nltk, scikit-learn, matplotlib, seaborn, wordcloud, kaggle

Setup

git clone <repo-url>

cd <repo>

pip install -r requirements.txt

Data
Download and unzip Sentiment140 via Kaggle CLI:
kaggle datasets download -d kazanova/sentiment140 --unzip -p data/

Usage
jupyter notebook Sentiment_Analysis_Project.ipynb

Output
Trained model saved as models/model.pkl

Structure
data/ raw/extracted CSV
models/model.pkl serialized best model
Sentiment_Analysis_Project.ipynb notebook with full pipeline
requirements.txt dependency list
README.md this file
