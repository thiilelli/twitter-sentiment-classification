# Twitter Sentiment Classification

Comparison of text vectorization methods for sentiment classification on Twitter data.

## Approach

Three vectorization strategies compared using Logistic Regression:
- TF-IDF
- Word2Vec (GloVe Twitter 25d)
- TF-IDF + POS tags

## Dataset

Twitter_Data.csv — 1000 samples (random_state=50)
Features: clean_text, category

## Setup

pip install -r requirements.txt

Open language_detection.ipynb in Jupyter or VS Code.

## License

MIT