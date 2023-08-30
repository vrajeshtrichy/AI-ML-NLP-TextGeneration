This repository contains two Jupyter notebook projects for text generation using Machine Learning and Natural Language Processing (NLP) techniques.

## Project 1: Article Generation with TensorFlow-Keras LSTM

This project demonstrates text generation using Long Short-Term Memory (LSTM) networks with TensorFlow and Keras. It generates text based on a dataset of headlines from the New York Times.

- [Notebook](Article-Generation-TensorFlow-Keras-LSTM/Article-Generation-TensorFlow-Keras-LSTM.ipynb)
- Original file is located at [Colab](https://colab.research.google.com/github/vrajeshtrichy/AI-ML-NLP-TextGeneration/blob/master/Article-Generation-TensorFlow-Keras-LSTM/Article-Generation-TensorFlow-Keras-LSTM.ipynb)

### Data Preparation

- Cleaned and processed the text data.
- Generated N-Grams for training data.

### LSTM Model

- Created an LSTM-based text generation model.
- Utilized dropout for better generalization.

### Training and Results

- Trained the model for 100 epochs.
- Generated text based on seed phrases.

#### Example Generated Texts

- "Cyclone" ➡ "Cyclone Harvey Could Bring Rainfall to Texas"
- "United States" ➡ "United States Sanctions Are Creating Tensions"
- "India and China" ➡ "India and China Clash Over Border Dispute"
- "New York" ➡ "New York City Marathon Prepares for a Big Day"
- "Science and Technology" ➡ "Science and Technology Advancements in the Modern World"

## Project 2: Poetry Generation with TensorFlow-Keras LSTM

This project focuses on generating poetry inspired by Shakespeare's works using LSTM networks.

- [Notebook](Poetry-TextGeneration-Using-TensorFlow-Keras-LSTM/Poetry-Generation-TensorFlow-Keras-LSTM.ipynb)
- Original file is located at [Colab](https://colab.research.google.com/github/vrajeshtrichy/AI-ML-NLP-TextGeneration/blob/master/Poetry-TextGeneration-Using-TensorFlow-Keras-LSTM/Poetry-Generation-TensorFlow-Keras-LSTM.ipynb)

### Data and Tokenization

- Downloaded and processed Shakespearean poetry data.
- Tokenized the text for model training.

### LSTM Model

- Created a bidirectional LSTM-based text generation model.
- Utilized an embedding layer for word representation.

### Training and Results

- Trained the model for 200 epochs.
- Generated poetry starting from a seed phrase.

### Generated Text Example

Seed Phrase: "It was a cold night."
Generated Text: "It was a cold night. Have seen this day they are they shall summer's part part with this this more live his state in his hate with thy worth with say may see thee be her love for to with him you then by thee to me live all the"

## Instructions

Feel free to explore the notebooks for detailed code and explanations. You can run them in Google Colab by clicking on the provided links.

Enjoy experimenting with text generation using these models!

