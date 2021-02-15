# Handwritten-digits-classification-using-neural-network

1.Import Dataset
2.Data Preproessing
3.Build CNN Model

I'm going to work through a series of simple neural network architectures and compare their performance on the MNIST handwritten digits dataset.take an input image (28x28 pixels) of a handwritten single digit (0–9) and classify the image as the appropriate digit.Here are some examples of the images in the dataset:

![Capture](https://user-images.githubusercontent.com/47972437/107970487-5e90c900-6fdb-11eb-982a-345d9795e9a0.PNG)
#Preparing the data
It's focused only on fully connected neural networks, which means our input data must be a vector. Instead of several 28x28 images, we’ll have several vectors that are all length 784 (28*28=784). The labels for this dataset are numerical values from 0 to 9
