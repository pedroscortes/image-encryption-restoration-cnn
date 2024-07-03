# Using a CNN for Image Encryption and Restoration

This repository was created as a way to study a little more about deep learning, convolutional neural networks and image restoration.

The inspiration for covering these topics was [this article](https://arxiv.org/abs/2406.16792) I found while exploring arXiv. It's really worth reading!


# MNIST

In the [cnn_encoder_mnist file](https://github.com/pedroscortes/image-encryption-restoration-cnn/blob/main/cnn_encoder_mnist.ipynb) you will find a simple code that I built using images from the [MNIST](https://www.tensorflow.org/datasets/catalog/mnist?hl=pt-br) benchmark image bank. 

The objective in this case was to encrypt these images using a convolutional neural network and then restore it trying to keep it as similar as possible to the original image. 

In addition, I also used some process evaluation metrics to verify effectiveness.

This was my first experience working with CNNs, so I kept the code as simple as possible.


# Brain Images

In the [brain_images](https://github.com/pedroscortes/image-encryption-restoration-cnn/tree/main/brain_images) folder you will find a slightly more robust algorithm that I built for the same purpose, but applied to [this image bank](https://www.kaggle.com/datasets/pkdarabi/brain-tumor-image-dataset-semantic-segmentation) that I found on Kaggle with thousands of medical images of patients' brains.

In this case, I worked with more elements in image encryption such as noise and chaos, as well as more performance metrics and measures to avoid overfitting.


# Convolutional Neural Networks

Convolutional Neural Networks (CNNs) are a type of deep learning model primarily used for analyzing visual data. They consist of multiple layers, including convolutional layers, pooling layers, and fully connected layers, designed to automatically and adaptively learn spatial hierarchies of features from input images. The convolutional layers apply filters to the input data to capture essential features such as edges, textures, and patterns. Pooling layers reduce the dimensionality of the data, making the network more computationally efficient and less prone to overfitting. Fully connected layers, often at the end of the network, integrate these features to make predictions or classifications. CNNs are widely used in image recognition, object detection, and other tasks involving image and video processing due to their ability to effectively capture and interpret complex visual patterns.

Read more [here.](https://doi.org/10.31763/ijrcs.v2i4.888)


