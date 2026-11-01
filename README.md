# Disaster Tweet Classification with RNN and LSTM

This notebook applies recurrent neural networks to binary disaster-tweet classification. It compares a SimpleRNN model with a bidirectional LSTM and reports test-set results.

## Workflow

1. Upload `tweets.csv` to the Google Colab session.
2. Clean and tokenize tweet text, then convert it to padded integer sequences.
3. Split the data into training and test sets and prepare class weights for imbalanced labels.
4. Train an embedding + SimpleRNN model and a bidirectional LSTM model with dropout and early stopping.
5. Review learning curves and the classification report.

The notebook uses a 20,000-token vocabulary, 64-dimensional embeddings, and a 64-unit recurrent layer in the model definitions. Adjustments to these settings can affect runtime and results.

## Dataset

Expected input: `tweets.csv`, with tweet text and a binary `target` label (`0` = not disaster-related, `1` = disaster-related). The dataset is not stored in this repository; provide it in Colab when prompted.

## Run in Google Colab

Open `disastertweetrnnlstm.ipynb`, upload the dataset, and run the cells from top to bottom. A GPU runtime is recommended for faster training. Install any missing dependencies reported by Colab.

## Repository contents

- `disastertweetrnnlstm.ipynb` — preprocessing, RNN/LSTM training, and evaluation.
- `README.md` — project overview and instructions.

## Author

Gizem Bektaş
