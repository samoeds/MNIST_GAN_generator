GAN to Generate Numbers Like in the MNIST Dataset

This repository contains an implementation of a Generative Adversarial Network (GAN) designed to generate realistic handwritten digits similar to those in the MNIST dataset. The project demonstrates how GANs can learn to create images from scratch by training a generator and a discriminator in an adversarial setup.

Features

Trains on the MNIST dataset of handwritten digits.

Generates 

28
×
28

28×28 grayscale images of digits (0-9).

Fully connected neural networks for both the generator and discriminator.

Implements key GAN techniques:
Batch normalization in the generator.
Leaky ReLU activations in the discriminator.
Binary cross-entropy loss with logits for stability.

Requirements

Python 3.8+
PyTorch
Torchvision
Matplotlib (for visualization)

How It Works

Generator: Creates synthetic images from random noise vectors.
Discriminator: Differentiates between real and generated images.
Training: Both networks are trained adversarially:
The generator tries to fool the discriminator.
The discriminator learns to identify real vs. fake images.