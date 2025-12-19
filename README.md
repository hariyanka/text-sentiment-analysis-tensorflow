# Text Sentiment Classification using TensorFlow

## Overview
This project implements a deep learning model to classify movie reviews as positive or negative using the IMDB dataset.

## Tech Stack
- Python
- TensorFlow / Keras
- IMDB Movie Reviews Dataset

## Model Architecture
Embedding → GlobalAveragePooling1D → Dense → Sigmoid

## Features
- Text preprocessing using tokenization and padding
- Binary sentiment classification
- Custom text inference
- Dataset-specific encoding alignment

## Learning Outcomes
- Understood NLP preprocessing pipelines
- Worked with embedding layers in TensorFlow
- Debugged and fixed inference issues caused by word index mismatch
- Learned importance of consistency between training and inference

## How to Run
Open the notebook in Google Colab and run all cells sequentially.

## Outcome
The model successfully predicts sentiment for unseen text inputs after correcting word index offset issues in preprocessing.
