# emnist-deep-learning-classification

# Description
This project was intended to explore the properties of convolution neural networks (CNN).I built a deep model to test the more challenging EMNIST dataset dataset ( set of handwritten character digits derived from the NIST Special Database 19 and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset)
from kaggle : https://www.kaggle.com/crawford/emnist/version/2

# Process:

-Load data from kaggle
-Data processing when i rechaped and  was scaling our dataset  for make our model more faster and less complex

-Used a data augmantation for more training data ,and callbacks to decide  to how and after how much epochs the model stop,to ensure that do not pass on   loss global minimal.

-Building a CNN model with multipl layes
test our model on test set

Accuracy reached 88.7% in  validation and 88.9% in testing

Plot a confusion matrix 




# Environment


GOOGLE GOLAB

Tensorflow 

Keras

pandas

Numpy

seabons


# Usage
EMNIST(1).ipynb

A training program for classifying the EMNIST dataset


