# Assignment13

This repository contains the Colab notebook for a basic generative text-model trained on a public-domain Project Gutenberg dataset (*Alice’s Adventures in Wonderland*).

## Contents
- `Assignment13.ipynb` — complete notebook with dataset download, preprocessing, model training, and text generation.
- Simple LSTM model for word-level text generation.
- Training loss plot and sample generated text included in the notebook.

## How to Use
1. Open the notebook in Google Colab.
2. Run all cells in order (requires: `tensorflow`, `numpy`, `pandas`, `requests`).
3. After training, use the `generate_text()` function to create new text from a seed prompt.
