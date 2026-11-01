# Disaster Tweet Classification with RNN and LSTM

This Google Colab notebook applies recurrent neural networks to binary disaster-tweet classification. It compares a SimpleRNN model with a bidirectional LSTM and reports test-set metrics.

## Workflow

1. Load the tweet data in Colab.
2. Clean and tokenize tweet text, then convert it to padded integer sequences.
3. Split data into training and test sets and prepare class weights for imbalanced labels.
4. Train embedding + SimpleRNN and bidirectional LSTM models with dropout and early stopping.
5. Review learning curves and the classification report.

The notebook uses a 20,000-token vocabulary, 64-dimensional embeddings, and 64-unit recurrent layers in its model definitions. Changing these settings can affect training time and results.

## Dataset

The notebook uses `tweets.csv`, with tweet text in `text` and a binary `target` label (`0` = not disaster-related, `1` = disaster-related). The CSV is included in this repository for convenient access.

The source is [Disaster Tweets by Viktor S on Kaggle](https://www.kaggle.com/datasets/vstepanenko/disaster-tweets), listed under **CC0 1.0 Public Domain**. It contains more than 11,000 tweets. The source notes that some text may be profane, vulgar, or offensive; see the Kaggle page for provenance and details.

## Run in Google Colab

1. Open `disastertweetrnnlstm.ipynb` in Google Colab.
2. Download `tweets.csv` from this repository and upload it when requested by the notebook.
3. Run the cells from top to bottom. A GPU runtime is recommended for faster training; install any missing dependencies reported by Colab.

The notebook reports results from its own execution. Metrics can vary with the data split, runtime, and training configuration.

## Repository contents

- `disastertweetrnnlstm.ipynb` — preprocessing, RNN/LSTM training, and evaluation.
- `tweets.csv` — CC0 disaster tweet dataset; source and license are linked above.
- `README.md` — project overview and instructions.

## Author

Gizem Bektaş
