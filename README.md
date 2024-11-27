# Anti-Hater Filter for Social Networks
This project aims to develop an automated moderation system based on Deep Learning techniques, capable of identifying and filtering toxic, offensive, or inappropriate comments in real-time within an online platform. The model is designed to classify comments into multiple relevant categories, ensuring effective management of harmful content without compromising the user experience.

# Key Features

## Text Preprocessing: 
The code includes various preprocessing steps to clean and normalize the textual data, such as removing URLs, HTML tags, non-alphabetic characters, tokenizing, removing stopwords, and lemmatizing words.

## Text Data Augmentation: 
To address class imbalance in the dataset, the code implements several text augmentation techniques, including synonym replacement, random insertion, random swap, and random deletion, to generate diverse variations of the minority class samples.

## Text Vectorization: 
The code uses the Keras Tokenizer to tokenize the text data and convert it into numerical sequences, which can be used as input to the machine learning model.

## Multichannel Convolutional Bidirectional GRU Model: 
The model architecture consists of multiple channels with different kernel sizes, enabling the simultaneous processing of various n-grams. It includes a word embedding layer, 1D-convolutional layers, dropout, max-pooling, a bidirectional GRU layer, and fully connected layers to effectively capture diverse linguistic patterns.

## Model Training and Evaluation: 
The code trains the model using the preprocessed and augmented data, with the provision to save and load the trained model. It also includes the evaluation of the model's performance on the test set, including the calculation of loss, f1 score, and the visualization of confusion matrices for each label.

