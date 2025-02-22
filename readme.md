# Movie Review Sentiment Analysis

## Overview
This project implements deep learning to analyze IMDB movie reviews and classify them as either positive or negative sentiment. It was created as part of a Kaggle competition focused on sentiment analysis in movie reviews.

## Project Structure
- `movie_reviews.ipynb`: Main project notebook containing data analysis and model development
- `data/`: Directory containing training and test data
  - `movie_reviews.csv`: 40,000 labeled training reviews
  - `test_data.csv`: 10,000 unlabeled test reviews
- `submission.csv`: Generated predictions file for Kaggle submission

## Results
- Training completed in 5 epochs
- Validation Accuracy: 88.42%
- Kaggle Public Score: 0.87666
- Kaggle Private Score: 0.87900

## Requirements
- TensorFlow 2.x
- Pandas
- Numpy
- NLTK
- Matplotlib
- scikit-learn

## Usage
1. Clone the repository
2. Install required packages
3. Run the notebook `movie_reviews.ipynb`
4. Predictions will be saved in `submission.csv`

## Model Architecture
- Embedding layer (10,000 words vocabulary)
- LSTM layer (64 units)
- Dense layer with sigmoid activation