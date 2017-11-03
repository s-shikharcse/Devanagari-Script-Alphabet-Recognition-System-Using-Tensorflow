# Deep-neural-network

Used Tensorflow python library to build a deep neural network for Devanagari character recognition.
Goal was to design a feed-forward network for handwritten character regonition of Devanagari script.

The labeled dataset was provided for training the model(i.e Test data) were consists of 10,000 PNG format images(320x320). 
After the training process our model predicts the correct label for the image provided from the validation data set.

    What is a labeled data? 
    Labeled data is a group of samples that have been tagged with one or more labels. Labeling typically 
    takes a set of unlabeled data and augments each piece of that unlabeled data with meaningful tags 
    that are informative. After obtaining a labeled dataset, machine learning models can be applied to 
    the data so that new unlabeled data can be presented to the model and a likely label can be guessed 
    or predicted for that piece of unlabeled data.

The png image given in dataset is read using python package: scikit-image, it converts the png image into numpy-ndarray

### Following analysis was done:
- Effect of increasing the number of hidden units in our artificial neural network.
- Effect of varying(increasing) the learning rate.
- Effect of changing the actiavation function type from Ramp to Sigmoid to Hyperbolic tangent activation function.
