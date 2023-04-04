# Next-Frame-Video-Prediction-with-Convolutional-LSTMs
How to build and train a convolutional LSTM model for next-frame video prediction with PyTorch. The PyTorch implementation of (this)[https://keras.io/examples/vision/conv_lstm/] project.

The Convolutional LSTM architectures bring together time series processing and computer vision by introducing a convolutional recurrent cell in a LSTM layer. In this example, we will explore the Convolutional LSTM model in an application to next-frame prediction, the process of predicting what video frames come next given a series of past frames.

For this example, we will be using the Moving MNIST dataset.


For next-frame prediction, our model will be using a previous frame, to predict a new frame.
