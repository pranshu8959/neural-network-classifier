Neural Network Classifier for Letters A, B, and C
Project Overview
This project is about building a simple neural network from scratch using just Python's NumPy library. The goal is to make it recognize basic images of the letters A, B, and C. We're not using big machine learning tools like TensorFlow or PyTorch here, just the basics to understand how neural networks work.

How the "Images" Work
For this project, our "images" are simple patterns of pixels for the letters A, B, and C. Each image is a small 5x6 grid, which means 30 pixels in total. These 30 pixels are then flattened into a single line (a 1D array) that the neural network can understand.

What This Project Does
Defines Letter Patterns: We create the pixel patterns for A, B, and C ourselves.

Builds a Simple Network: It's a two-layer neural network, meaning it has an input, a "hidden" layer, and an output layer.

Uses Sigmoid Activation: Inside the network, a special function called "sigmoid" helps process the information.

Trains with Backpropagation: The network learns by a process called "backpropagation." This involves adjusting its internal settings (called weights) to reduce how many mistakes it makes when classifying letters.

Tracks Progress: While the network learns, we keep an eye on its "loss" (how wrong it is) and "accuracy" (how right it is) over time. We then show these as graphs.

Predicts and Shows Images: After training, the network can guess which letter an image represents. We can even show the image using matplotlib to see what the network was looking at when it made its prediction.

Why This Project is Important
This project helps you get hands-on experience with the basic building blocks of neural networks, such as:

Doing calculations with matrices (like grids of numbers).

Setting up the network's starting values.

Using activation functions (like sigmoid).

Calculating how wrong the network's guesses are (loss).

And making the network smarter by adjusting its settings (gradient descent).