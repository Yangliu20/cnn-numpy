# cnn-numpy
This project builds a simple convolutional neural network (CNN) **from scratch using NumPy** to classify handwritten digits in MNIST datasets. The code presents an end-to-end machine learning process, including image preprocessing, model definition, model training, model validation and inference. Forward propagation and backward propagation are written from scratch using pure numpy. 

## Model design
A simple CNN is implemented from scratch. It takes the 28*28 image as the input, normalizes it, and passes it through layers: 
- convolutional layer + relu
- max/average pooling layer
- flatten
- fully connected layer 1 + relu
- fully connected layer 2
- softmax

## Model training
Trainig uses only one CPU considering the small model size. 

Convergence plot

![image](https://github.com/user-attachments/assets/0d2d29ed-8a0e-4e50-87ae-32c914d36cee)


## Model evaluation
Test accuracy 86.26%

Confusion matrix

![image](https://github.com/user-attachments/assets/0400c946-d8f6-4fbc-b64c-bb13ec93e6d4)
