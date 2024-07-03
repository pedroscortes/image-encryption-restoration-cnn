# Using a CNN for Image Encryption and Restoration

This repository was created as a way to study a little more about deep learning, convolutional neural networks and image restoration.

The inspiration for covering these topics was [this article](https://arxiv.org/abs/2406.16792) I found while exploring arXiv. It's really worth reading!


In the [cnn_encoder_mnist file](https://github.com/pedroscortes/image-encryption-restoration-cnn/blob/main/cnn_encoder_mnist.ipynb) you will find a simple code that I built using images from the [MNIST](https://www.tensorflow.org/datasets/catalog/mnist?hl=pt-br) benchmark image bank. 

The objective in this case was to encrypt these images using a convolutional neural network and then restore it trying to keep it as similar as possible to the original image. 

In addition, I also used some process evaluation metrics to verify effectiveness.

This was my first experience working with CNNs, so I kept the code as simple as possible.


In the [brain_images](https://github.com/pedroscortes/image-encryption-restoration-cnn/tree/main/brain_images) folder you will find a slightly more robust algorithm that I built for the same purpose, but applied to [this image bank](https://www.kaggle.com/datasets/pkdarabi/brain-tumor-image-dataset-semantic-segmentation) that I found on Kaggle with thousands of medical images of patients' brains.

In this case, I worked with more elements in image encryption such as noise and chaos, as well as more performance metrics and measures to avoid overfitting.


