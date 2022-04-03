# LSTM and Bidirectional LSTM for Regression

This repo works you throught what LSTM networks are and how to build a bidirectional network. Note that we can mention LSTM as an extension to RNN, but keep in mind that it is not the only extension. For instance, Attention models, Sequence-to-Sequence RNN are examples of other extensions.

To demonstrate a use-case where LSTM and Bidirectional LSTM can be applied in a real example, we will solve a regression problem predicting the number of passengers using the taxi cars in New York City. We can predict the number of passengers to expect next week or next month and manage the taxi availability accordingly.

LSTM is helpful for pattern recognition, especially where the order of input is the main factor. We will see in the provided an example how to use Keras [2] to build up an LSTM to solve a regression problem.

LSTM for regression in Machine Learning is typically a time series problem. The critical difference in time series compared to other machine learning problems is that the data samples come in a sequence. The sequence represents a time dimension explicitly or implicitly. The implicit part is the timesteps of the input sequence.

Note that LSTM models can be used to detect a cyber breach or unexpected system behavior, or fraud in credit card transactions. In these contexts, LSTM has one goal: predicting events that do not conform to expected patterns.
