Sentiment Analysis with Temporal Convolutional Networks (TCNs)
This project tackles sentiment analysis with a novel approach: utilizing Temporal Convolutional Networks (TCNs) instead of the commonly used recurrent neural networks (RNNs) like LSTMs.

Why TCNs?

RNNs have dominated sequence modeling tasks like sentiment analysis, but TCNs offer distinct advantages:

Efficiency: TCNs can be parallelized more efficiently, leading to faster training compared to RNNs.
Long-range Dependencies: TCNs excel at capturing long-range dependencies within sequences, crucial for understanding sentiment in text.
Innovation: This project implements a new sentiment analysis model using TCNs, offering a fresh perspective.
Our Approach

This project breaks away from the standard RNN-based approach for sentiment analysis and leverages TCNs. Here's a breakdown:

Data Preprocessing:

We download the IMDB movie review dataset.
Text is converted to numerical features using CountVectorizer for preprocessing.
The data is then split into training and validation sets.
TCN Model Architecture:

Inspired by the architecture provided in https://github.com/locuslab/TCN (used for reference only), we build a custom TCN model.
This model employs temporal convolutional blocks designed to extract sentiment-bearing features from the sequence of words.
Training and Evaluation:

The TCN model is trained on the training data using the Adam optimizer and cross-entropy loss function.
The model's performance is evaluated on the validation set by calculating accuracy.
How to Use It

The code is structured within a Jupyter Notebook (.ipynb) file. It likely includes:

Data loading and preprocessing functions.
The custom TCN model definition tailored for sentiment analysis.
Training and evaluation routines.
To run the sentiment analysis model, you would execute the Jupyter Notebook. This notebook would allow customization by providing options to control hyperparameters.

In essence, this project explores a groundbreaking approach to sentiment analysis using TCNs, offering an efficient and effective alternative to RNNs.

