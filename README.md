This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) using TensorFlow to generate realistic-looking handwritten digits using the MNIST dataset.

A DCGAN is composed of two competing neural networks:
Generator: Generates fake images from random noise.
Discriminator: Tries to distinguish between real and fake images.
Through adversarial training, the generator learns to produce images that resemble real handwritten digits.

The project uses the MNIST dataset:
- 60,000 grayscale images of handwritten digits (28x28 pixels)
- Labels from 0 to 9 (labels are unused in vanilla GAN)
