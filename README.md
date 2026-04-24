# Twitter Sentiment Classification

Comparison of text vectorization methods for sentiment classification on Twitter data.

## Results

Trained on a 1000-sample subset (random_state=50) — 3 classes: positive, neutral, negative.

| Method | Accuracy |
|---|---|
| TF-IDF | 57.5% |
| Word2Vec (GloVe 25d) | 51.5% |
| TF-IDF + POS tags | **62.0%** |

> Note: trained on a 1000-sample subset. Full dataset (162k tweets) expected to yield higher accuracy.

## Approach

Three vectorization strategies compared using Logistic Regression:
- TF-IDF
- Word2Vec (GloVe Twitter 25d)
- TF-IDF + POS tags (one-hot encoded)

## Dataset

Twitter_Data.csv — 162,969 tweets, 3 sentiment classes (positive, neutral, negative).

## Setup

pip install -r requirements.txt

Open language_detection.ipynb in Jupyter.

## License

MIT