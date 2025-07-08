# 🧠 MNIST Digit Generator using GAN (PyTorch)

This project implements a simple Generative Adversarial Network (GAN) in PyTorch to generate handwritten digit images similar to the MNIST dataset. The generator learns to produce fake images that resemble real MNIST digits, while the discriminator learns to distinguish real images from fakes.

---

## 📌 Description

This project trains a GAN model consisting of two neural networks:

- **Generator (G)**: Takes random noise and generates images resembling handwritten digits.
- **Discriminator (D)**: Tries to differentiate between real and fake MNIST images.

The training is adversarial: the generator tries to fool the discriminator, while the discriminator tries to detect fake images. Over time, both networks improve in performance, and the generator learns to produce high-quality digit images.

---

## 🧪 Requirements

- Python 3.6+
- PyTorch
- torchvision
- matplotlib
- numpy
---
