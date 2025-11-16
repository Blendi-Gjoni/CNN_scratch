Handwritten Digit Recognition using a Simple Neural Network (CNN-like Implementation)
--
This project implements a basic neural network from scratch in Python to recognize handwritten digits (0-9) from the MNIST dataset. It uses NumPy, Pandas, and Matplotlib for data manipulation, training, and visualization.

Features
--
Implements a simple fully connected neural network with:

Input layer (784 neurons for 28x28 pixel images)

One hidden layer (64 neurons, configurable)

Output layer (10 neurons corresponding to digits 0-9)

Uses ReLU activation in hidden layer

Uses Softmax activation in output layer

Implements forward pass, backward pass, and gradient descent from scratch

Tracks accuracy during training

Can visualize predictions for individual images

Requirements
--

Make sure you have the following Python libraries installed:

pip install numpy pandas matplotlib

Dataset
--

The network is trained on the MNIST dataset. You need to download the dataset from Kaggle:

https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

After downloading, place the dataset folder in the main root directory of the project, named dataset/:

How to Run
--
Clone the repository or copy the project files.

Download the MNIST CSV dataset and place it in the dataset/ folder.

Run the Jupyter Notebook, CNN.ipynb

The network will train for 500 iterations, printing the accuracy every 50 iterations.

You can test predictions on specific images using the test_prediction(index, W1, b1, W2, b2) function.
When predicting, use only values 0-59999

Example
--
After training, running:

test_prediction(5, W1, b1, W2, b2)


might output:

Prediction: [2]
Label: 2


And display the corresponding 28x28 image.
