# Deep-Learning-Computer-Vision

In this project use deep neural network in different problems with a different techniques

---
### 1 - [Keras-ANN-bank_note_data.ipynb](https://nbviewer.jupyter.org/github/ahmedatef1610/Deep-Learning-Computer-Vision/blob/master/00-Keras-ANN-bank_note_data.ipynb) 

We will use the Bank Authentication Data Set to start off with. This data set consists of various image features derived from images that had 400 x 400 pixels. You should note the data itself that we will be using ARE NOT ACTUAL IMAGES, they are features of images. In the next lecture we will cover grabbing and working with image data with Keras. This notebook focuses on learning the basics of building a neural network with Keras.

More info on the data set:

https://archive.ics.uci.edu/ml/datasets/banknote+authentication

Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

Attribute Information:

1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)


---

### 2 - [Keras-CNN-MNIST.ipynb](https://nbviewer.jupyter.org/github/ahmedatef1610/Deep-Learning-Computer-Vision/blob/master/01-Keras-CNN-MNIST.ipynb) 

MNIST Handwritten Digit Classification Dataset [link](http://yann.lecun.com/exdb/mnist/)

The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset.

It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.

The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.

---

### 3 - [Keras-CNN-CIFAR-10.ipynb](https://nbviewer.jupyter.org/github/ahmedatef1610/Deep-Learning-Computer-Vision/blob/master/02-Keras-CNN-CIFAR-10.ipynb) 

CIFAR-10 Multiple Classes [link](https://www.cs.toronto.edu/~kriz/cifar.html)

Let's go over another example of using Keras and building out CNNs. 

This time will use another famous data set, the CIFAR-10 dataset which consists of 10 different image types. 

The Data CIFAR-10 is a dataset of 50,000 32x32 color training images, labeled over 10 categories, and 10,000 test images.

---

### 4 - [Deep-Learning-Custom-Images.ipynb](https://nbviewer.jupyter.org/github/ahmedatef1610/Deep-Learning-Computer-Vision/blob/master/03-Deep-Learning-Custom-Images.ipynb) 

Working with Custom Images

So far everything we've worked with has been nicely formatted for us already by Keras.

Let's explore what its like to work with a more realistic data set.

ORIGINAL DATA SOURCE: [link1](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765) [link2](https://drive.google.com/file/d/1U6RtBhML-Lj0w2suve0UhQmwcF5pfJCm/view)

The Kaggle Competition: [Cats and Dogs](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/overview/description) includes 25,000 images of cats and dogs. We will be building a classifier that works with these images and attempt to detect dogs versus cats!

The pictures are numbered 0-12499 for both cats and dogs, thus we have 12,500 images of Dogs and 12,500 images of Cats. This is a huge dataset!!

And we use keras preprocessing image ImageDataGenerator to make image augmentation

---

### 5 - [Keras-CNN-FASHION-MNIST.ipynb](https://nbviewer.jupyter.org/github/ahmedatef1610/Deep-Learning-Computer-Vision/blob/master/04-Keras-CNN-FASHION-MNIST.ipynb) 

Your task is to build an image classifier with Keras and Convolutional Neural Networks for the Fashion MNIST dataset. 

This data set includes 10 labels of different clothing types with 28 by 28 grayscale images. There is a training set of 60,000 images and 10,000 test images.


| Label | Description |
| ------------- | ------------- |
| 0     |  T-shirt/top  |
| 1     |  Trouser |
| 2     |  Pullover  |
| 3     |  Dress  |
| 4     |  Coat |
| 5     |  Sandal |
| 6    |   Shirt  |
| 7    |   Sneaker |
| 8  |     Bag |
| 9   |    Ankle boot  |


---

depend on [Jose Portilla course](https://www.udemy.com/course/python-for-computer-vision-with-opencv-and-deep-learning/)
