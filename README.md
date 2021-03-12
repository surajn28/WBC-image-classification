# WBC-image-classification:
Project Specifications:
Python - version 3.5
TensorFlow 2.0
Keras 2.3.0

The fild of hematology involves the analysis of blood and its components
like platelets, red blood cells, white blood cells. The outcome of
this analysis can be vital in determining the condition of the human
body and it is important to obtain accurate results. This project involves the analysis of white blood cells (WBC) using
deep learning techniques. The proposed ’one vs all’ classification approach combined with
a 3-class CNN classifier has yielded very promising results with a
combined accuracy 95.45% in WBC identification and 90.49% in WBC
differential classification.

**4-class CNN cell classification**
This is a straightforward approach in which all the four classes are
classified together using a single convolutional neural network.
The training data of the blood samples containing four classes are
fed into a single convolutional network after the data pre-processing.
As the kernel passes over the images neural network learns the features
of four different classes and classifies them.

**OVA and 3-class CNN cell classification**
This design approach involves two different convolutional neural
networks. One convolutional neural network is built for the classification
of single white blood cells/ monocytes and the other neural network is used to classify the rest of the classes.

**Multi-channel convolutional neural network classification**
This method is implemented with a purpose to make the neural
network learn more features with the use of multiple images in multiple
channels. 5 input channels are with different images.

**Multi-input convolutional neural network classification**
This method is implemented with a purpose to make the neural
network learn more features with the use of multiple images in are used in
three different input layers instead of using them in multiple channels
in a single input layer.
