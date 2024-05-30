# CRED
 # Requirements
  # Required Packages
    1.python3
    2.TensorFlow 1.13
    3.keras 2.2.4
    4.pandas
    5.scikit-learn
    6.gensim
  Run the following script to install the required packages.
  + pip install --upgrade pip
  + pip install --upgrade tensorflow
  + pip install keras
  + pip install pandas
  + pip install scikit-learn
  + pip install gensim
# Required Dataset
  We prepared dataset for experiments.(https://github.com/Messi-Q/ReChecker)
# Overview
  My attempt to detect smart contract reentrancy vulnerability. We apply deep learning to smart contract vulnerability detection. So far, we have completed the following work:
  + Uses N-grams and deep learning network to train detection model, include GCN, RNN, LSTM, BLSTM, and BiLSTM-Att.
  + Implemented a tool to automatically constructe cross-contract reentrancy semantic graph.
    + Constructe cross-contract semantic graph.
    + RCSG are vectorized for input to neural network.
  + Trained RCSG to detect reentrancy vulnerability.
