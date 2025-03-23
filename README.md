### Sentiment Analysis Using IMDB Review Classification with ANN

### Overview:
This project involves performing sentiment analysis on the IMDB movie review dataset using a simple Artificial Neural Network (ANN). The primary goal is to classify reviews into two categories: Positive and Negative. After preprocessing the textual data, the model was trained to achieve a validation accuracy of 0.937. The model was further evaluated using out-of-sample predictions, successfully classifying unseen reviews.

### Steps:

#### Data Collection and Class Mapping:

1. IMDB movie reviews dataset was used.

2. Sentiments were labeled as Positive (1) and Negative (0).

#### Text Preprocessing:

1. Tokenization of the text data.

2. Splitting the dataset into training and testing sets.

3. Stemming to reduce words to their root form.

4. One-hot encoding of the reviews for representation.

5. Padding of the encoded sequences to ensure uniform input length.

#### Model Construction:

A simple ANN was constructed using the following layers:

1. Embedding Layer for word representation.

2. Hidden layers for feature extraction.

3. Output layer with a sigmoid activation function for binary classification.

#### Model Compilation and Training:

1. The model was compiled using the Binary Cross-Entropy loss function.

2. Adam Optimizer was used to ensure efficient learning.

3. Training was performed for a specified number of epochs with validation.

#### Evaluation:

The model achieved a validation accuracy of 0.937.

#### Prediction:

1. Out-of-sample predictions were performed.

2. After applying the same text preprocessing steps to test data, the model accurately classified a review as Positive.

### Result:
The sentiment analysis model built using ANN demonstrated excellent accuracy in classifying movie reviews. With a validation accuracy of 0.937, the model shows robust generalization to unseen data, making it an effective solution for sentiment classification tasks. The successful prediction of an out-of-sample test review further validates the model’s performance.
