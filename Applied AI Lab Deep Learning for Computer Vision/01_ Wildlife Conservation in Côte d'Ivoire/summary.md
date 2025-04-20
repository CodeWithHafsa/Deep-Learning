## 1 - Image as data

**Summary:** In this lesson, we'll learn how to work with tensors in PyTorch. We'll also explore the dataset for this project, focusing on how images are represented in tensors.

**Objectives:**
* Check important attributes of tensors, such as size, data type, and device.
* Manipulate tensors through slicing.
* Perform mathematical operations with tensors, including matrix multiplication and aggregation calculations.
* Download and decompress the dataset for this project.
* Load and explore images using PIL.
* Demonstrate how visual information is stored in tensors, focusing on color channels.

**New Terms:**
* Attribute
* Class
* Color channel
* Method
* Tensor

## 2 - What Are Python Tracebacks?

In Python, a traceback is a detailed report generated when an error occurs in your code. A traceback, also called a stack trace, offers valuable information about what and where went wrong in the code by providing a step-by-step account of what lead up to the Python raising an exception. While tracebacks may appear daunting at first glance, they contain crucial details that can significantly aid in debugging your code.

By carefully examining a traceback, you can:

* Understand the nature of the exception
* See the sequence of code that led to the error
* Identify the exact line where the error occurred, sometimes even where in the line the error occurred

Learning to read and understand tracebacks is an essential skill for Python developers because it's one of the primary ways to debug errors in Python code.

## 3 - Binary Classification with PyTorch

**Summary:** In this lesson, we'll continue using PyTorch and build our very first neural network model. We'll use this model to classify if a wildlife camera image shows a hog or not.

**Objectives:**
* Convert images from grayscale to RGB
* Resizes images
* Create a transformation pipeline to * standardize images for training
* Build and train a simple neural network model in PyTorch
* Save our trained neural network to disk

**New Terms:**
* Activation function
* Automatic differentiation
* Backpropagation
* Binary classification
* Cross-entropy
* Epoch
* Layers
* Logits
* Optimizer

## 04 - Multiclass Classification
**Summary:** In this lesson, we'll work with the full wildlife dataset, which has eight classes. This is more than the network in the previous notebook can handle. Here we'll build and train a more complicated neural network, called a Convolutional Neural Network, that is meant for working with images. We'll use this network to get the predictions we need for the competition at DrivenData.org.

**Objectives:**
* Read in data with multiple classes
* Normalize our data to improve performance
* Create a Convolutional Neural Network that works well with images
* Train that network to do multiclass classification
* Reformat the network predictions to complete the competition

**New Terms:**
* Multiclass
* Normalize
* Convolution
* Max pooling