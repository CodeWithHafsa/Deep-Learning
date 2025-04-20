## 01 - Common Errors In PyTorch Sequential Model

PyTorch's `n.Sequential` offers a streamlined method for constructing neural networks. This sequential approach is particularly effective for crafting straightforward architectures where each layer directly feeds into the subsequent one. However, when building these models, it's crucial to exercise caution, as inadvertent layer sizing issues can result in runtime errors or unexpected model behavior.

We'll consider the following common error scenarios when constructing a PyTorch Sequential model:

* Incorrect layer sizing, both in the input layer and after flattening a convolutional layer
* Accidental layer duplication
* Forgetting to flatten between convolutional and linear layers

These scenarios will emphasize the importance of paying careful attention and verification when creating neural network architectures.

## 02 - Exploring the Cassava Disease Dataset

**Summary:** In this lesson, we'll explore the dataset for this project. We'll be looking at images of crops in Uganda, some healthy and some with different diseases. We'll also prepare the data for later lessons.

**Objectives:**
* Check the properties of our image data
* Normalize the data set
* Check the number of data points in each class
* Balance the classes, so each has the same number of observations

**New Terms:**
* Unbalanced classes
* Undersampling

##  03 - Deep Neural Network

**Summary:** In this lesson, we'll continue using images of crop disease from Uganda. We'll build a convolutional neural network and train it to classify images into one of five classes. We'll take this lesson as an opportunity to highlight the dangers of overfitting.

**Objectives:**
* Convert images from grayscale to RGB
* Resize images
* Normalize our data
* Create a transformation pipeline to standardize images for training
* Create a Convolutional Neural Network
* Train the network to do multiclass classification
* Identify overfitting

**New Terms:**
* Overfitting
* Learning curve

##  04 - Transfer Learning and Cross Validation
**Summary:** In this lesson, we'll further improve our model using Transfer Learning. We'll take a publicly available image classification model that someone else has already trained and alter it to meet our needs. We'll only need to train the altered part, vastly improving both our training speed and model performance. We'll evaluate the model's performance with the more robust k-fold cross-validation method.

**Objectives:**
* Load our competition data
* Download a pre-trained model
* Alter that model to suit our needs with Transfer Learning
* Train just the altered part
* Test model performance with k-fold cross-validation

**New Terms:**
* Pre-trained model
* Transfer learning
* K-fold Cross validation

## 05 - Transfer Learning and Callbacks
**Summary:** In this lesson, we'll build another classifier model that predicts the crop disease on images of cassava plants from Uganda. We'll again use Transfer Learning, where a model trained for a task is reused as the starting point for a model on a different task. We'll also delve into Callbacks, which are powerful tools to customize the behavior of your model during training. Specifically, we'll focus on Learning Rate Scheduling, Checkpointing, and Early Stopping to enhance our model's training process.

**Objectives:**
* Read in data with multiple classes
* Transform data and prepare it for training
* Use Transfer Learning to train a classifier model on cassava images
* Improve training by implementing various callbacks
* Prepare a submission for our competition by reformatting network predictions on the test set

**New Terms:**
* Callbacks
* Learning Rate Scheduling
* Checkpointing
* Early Stopping

## 06 - Data Pollution & Power
The following is a fragment from the white paper [Data Pollution & Power (2022)](https://gryhasselbalch.com/books/data-pollution-power-a-white-paper-for-a-global-sustainable-development-agenda-on-ai/) published by the Bonn Sustainable AI Lab, Institute for Science and Ethics, University of Bonn.

References
Hasselbalch, G. (2022) Data Pollution & Power – White Paper for a Global Sustainable Agenda on AI, The Sustainable AI Lab, Bonn University.