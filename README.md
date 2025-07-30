CMEPredict – Adapted Notebook for CME Prediction Using RNNs
This notebook is based on the original CMEPredict project developed by Professor Jason T. L. Wang and his research team. The original tool models the prediction of coronal mass ejections (CMEs) using vector magnetic field data and recurrent neural networks (RNNs) such as GRUs and LSTMs.

As part of my coursework and hands-on learning, I downloaded this notebook from the Community Coordinated Software Center (CCSC) at NJIT as directed by Professor Wang. He instructed me to explore the tools on the site and report on how they function.

I have adapted and executed the original notebook to gain practical experience in:

Deep learning with time-series data

Using GRU and LSTM models for binary classification

Interpreting model performance through confusion matrices and ROC curves

Installation on Local Machine
To run this notebook locally, you will need Python 3.9 (tested with 3.9.13). Install the dependencies with:

bash
Copy
Edit
pip install -r requirements.txt
Or install packages manually:

Library	Version	Description
numpy	1.21.6	Data processing
pandas	1.4.4	Data analysis
scikit-learn	1.0.2	ML tools for preprocessing/evaluation
matplotlib	3.5.2	Visualization
tensorflow	2.11.0	Neural network framework
keras	2.11.0	High-level neural network API

Original Project Source
This notebook is adapted from the CMEPredict tool published here:
https://github.com/deepsuncode/RNN-CME-prediction
DOI: 10.5281/zenodo.5643647

Full paper:
Predicting Coronal Mass Ejections Using SDO/HMI Vector Magnetic Data Products and Recurrent Neural Networks
Authors: Hao Liu, Chang Liu, Jason T. L. Wang, Haimin Wang
Read paper on IOPscience

Objective and Summary
The goal of this notebook is to use physical features extracted from solar active regions to predict whether an M- or X-class flare will result in a CME. We model these time-series data using GRU and LSTM RNN architectures and evaluate their performance.

This project was assigned as an exploratory learning task and aligned with real-world data science and machine learning model evaluation practices.

