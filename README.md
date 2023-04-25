# Reuters news Classification - Neural Networks

This repository contains a Jupyter notebook that demonstrates how to use neural networks to classify Reuters news articles into different topics. The notebook uses the Reuters-21578 dataset, which is a collection of over 20,000 news articles that have been manually categorized into different topics, such as "earnings," "money-fx," "crude," "grain," etc.

The notebook shows how to preprocess the text data by tokenizing the words, removing stop words, and converting the text into numerical vectors. It then builds a feedforward neural network using the Keras library and trains it on the preprocessed data. The notebook uses one-hot encoding to represent the topics and applies the softmax activation function to the output layer to produce a probability distribution over the topics.

The notebook evaluates the performance of the model on a test set and reports the accuracy, precision, recall, and F1 score for each topic. It also shows how to use the model to predict the topic of new news articles.

## Requirements
To run the notebook, you need to have Python 3.x installed on your system and the following libraries:

1. pandas
2. numpy
3. matplotlib
4. scikit-learn
5. keras
6. tensorflow

You can install these libraries using pip or conda. For example:

- pip install pandas numpy matplotlib scikit-learn keras tensorflow

## Usage
To use the notebook, you can either download the repository or clone it to your local machine. Then, open the Jupyter notebook in your browser and run the code cells in order.

The notebook assumes that the Reuters-21578 dataset is stored in a subdirectory named "data" in the same directory as the notebook. If you don't have the dataset, you can download it from here and extract it to the "data" directory.


## Acknowledgments
This notebook is based on the work of Nils Reimers, who developed a similar notebook for the AG News dataset. The Reuters-21578 dataset was originally compiled by David Lewis and his colleagues at the University of Massachusetts Amherst. The dataset is available from the UCI Machine Learning Repository.

