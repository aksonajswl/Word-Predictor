# Word-Predictor

# Word Prediction RNN

This project implements a simple Recurrent Neural Network (RNN) for **word prediction** using PyTorch. It uses tokenized text data to predict the next word in a sequence, which can be a useful task for many natural language processing (NLP) applications.

## Features

- **Word Prediction**: Predict the next word in a sequence based on previous words.
- **Model Architecture**: Uses an RNN with word embeddings and hidden states.
- **Training**: The model is trained using Cross-Entropy Loss for a classification task.
- **Reproducibility**: Seed is set to ensure reproducibility of results.

## Requirements

To run this project, you'll need Python and the following packages:

- Python 3.x
- PyTorch
- NumPy
- random
- (optional) Google Colab for GPU usage

You can install the dependencies using `pip`:

```bash
pip install -r requirements.txt
