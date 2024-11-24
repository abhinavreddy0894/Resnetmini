# Resnet_Model
This project implements a simplified version of a ResNet-like architecture, referred to as ResNet50. In ResNet50, the core idea of residual blocks is employed to overcome the issue of vanishing gradients and enable the training of very deep networks. As networks become deeper, it becomes harder to train them effectively due to the degradation problem, where accuracy starts to decrease as more layers are added. The solution introduced in ResNet (and used in ResNet50) is the residual connection (or skip connection), where the input is added to the output of a set of layers. This helps the network to focus on learning the residual (difference) between the input and the desired output, rather than learning the entire transformation.
# About Dataset
Tiny ImageNet is a downsized version of the ImageNet dataset designed for teaching and research purposes, particularly for courses like Stanford’s CS231N: Convolutional Neural Networks for Visual Recognition. It provides a manageable alternative to the full ImageNet dataset, making it suitable for quick experimentation and education in deep learning and computer vision.
Dataset Link: https://www.image-net.org/download-images.php
