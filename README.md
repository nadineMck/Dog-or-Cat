**Cat vs Dog Image Classification using CNN**
A machine learning project that classifies images as either cats or dogs using a Convolutional Neural Network (CNN) implemented in PyTorch.


**Overview**
This project implements a CNN to classify images of cats and dogs. The model should achieve good accuracy through a combination of convolutional layers for feature extraction and fully connected layers for classification, if i were using the big dataset for training, but due to internet issues, i was unable to do so.

**Model Architecture**
The CNN consists of:

4 convolutional blocks with increasing filter sizes (32 → 64 → 128 → 256)
Each block includes:

Conv2d layer with 3x3 kernel
ReLU activation
MaxPool2d for spatial dimension reduction


2 fully connected layers with dropout for classification
Final output layer with 2 neurons (dog/cat)

**To tran the model, you should:**
  -Organize your dataset as follows:
  dataset/
    train/
        dogs/
            dog1.jpg
            dog2.jpg
            ...
        cats/
            cat1.jpg
            cat2.jpg
            ...
    valid/
        dogs/
            dog1.jpg
            ...
        cats/
            cat1.jpg
            ...
    test/
        dogs/
            dog1.jpg
            ...
        cats/
            cat1.jpg
            ...
For Installation:
git clone https://github.com/nadineMck/Dog-or-Cat.git
cd Dog-Or-Cat

**I am tired, i need to sleep! But one can take the functions from the notebook and put them as separate functions files in github also, so that people can download them and use them easily**


**Make sure to change the path for the data in the code**
