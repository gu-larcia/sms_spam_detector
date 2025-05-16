# SMS Spam Classification

A simple machine learning application that classifies SMS messages as either spam or ham (not spam).

## Description

This project uses a machine learning model to predict whether a text message is spam or not. It employs a TF-IDF vectorizer combined with a Linear Support Vector Classification algorithm to make predictions.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- gradio

## Setup

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install pandas scikit-learn gradio
   ```
3. Ensure the `SMSSpamCollection.csv` file is in the `Resources` folder

## Usage

Run the Jupyter notebook `gradio_sms_text_classification.ipynb` to:
1. Train the model on the SMS dataset
2. Launch the Gradio web interface
3. Enter text messages to classify them as spam or ham

## Model Performance

The current model achieves approximately 75% accuracy on test examples. Future improvements could include:
- Feature engineering to improve classification accuracy
- Testing different classification algorithms
- Implementing cross-validation for better model evaluation
- Expanding the training dataset
