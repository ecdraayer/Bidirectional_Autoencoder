## Bidirectional_Autoencoder

This repository hosts the code for Bidirectional Recurrent Neural Network Autoencoders. 

This work directly builds up http://people.cs.aau.dk/~byang/papers/IJCAI2019.pdf which was the first paper to propose a 
method for creating an ensemble of sparesely connected RNN autoencoders to do time series anomaly detection. The work 
contained in this repository expanded upong their two methods, IF and SF, to create an ensemble of sparsely connected
bidirectional RNN autoencoders. 

## Repository Structure
* **feedforward_ae.py**: method Rand-Net which is a feed forward neural network used for time series anomlay detection
* **CNN_ae.py**: Convolutional Neural Network approach for time series anomaly deteciton
* **LSTM_ae.py**: Single LSTM RNN approach for time series anomaly detection
* **IF-SF_ae.py**: Original sparsely connected RNN ensemble methods proposed in http://people.cs.aau.dk/~byang/papers/IJCAI2019.pdf
* **Bidirectional_IF-SF_ae.py**: Newly proposed Bidirectional sparsely connected RNN ensemble methods
* **utils.py**: Utility functions used to read in data and process it for input for the neural network methods. 
* **NAB**: This folder contains a small sample of the NAB dataset used in the benchmarking of these algorithms. Links to the full dataset can be found in the paper.

## Dependencies
Python 3.5
TensorFlow 1.4.0
Scikit-learn 1.19
Pandas
Numpy


## How to Run:
