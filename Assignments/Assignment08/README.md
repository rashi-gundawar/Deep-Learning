# Assignment 08 – Pretrained BERT for Sentiment Analysis

## Objective
To implement a pretrained BERT model for sentiment analysis and classify movie reviews as positive or negative.

## Dataset
**IMDb Movie Reviews Dataset**
The dataset contains movie reviews with two sentiment classes:
- `0` – Negative
- `1` – Positive
For faster beginner-level training, a smaller subset of the dataset was used:
- Training Samples: 1000
- Testing Samples: 300

## Model Used
**BERT-base-uncased**
BERT (Bidirectional Encoder Representations from Transformers) is a pretrained Transformer-based language model. The pretrained BERT model is fine-tuned for binary sentiment classification.

## Tasks Performed

- Loaded the IMDb movie review dataset
- Selected a smaller training and testing dataset
- Loaded the pretrained BERT tokenizer
- Tokenized the movie reviews
- Applied truncation and padding
- Loaded the pretrained BERT model
- Fine-tuned BERT for sentiment classification
- Generated predictions on test data
- Evaluated model performance
- Generated a classification report
- Tested the model on custom movie reviews
- Saved the fine-tuned BERT model

## Evaluation Metrics
The model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

## Technologies Used
- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- NumPy
- Scikit-learn
