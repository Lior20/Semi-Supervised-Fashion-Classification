# VAE and GAN Project 📊🖼️

This project explores the implementation of Variational Autoencoders (VAEs) for semi-supervised learning and Generative Adversarial Networks (GANs) for image generation. 🧠🎨

## Project Structure 🗂️

The project is divided into two main parts:

1. **VAE for Semi-Supervised Learning** 🤖📚:
   - Implements a Variational Autoencoder (VAE) model for feature extraction.
   - Trains a transductive SVM classifier on the latent representations of the labeled data.
   - Evaluates the semi-supervised learning approach on the FashionMNIST dataset with varying numbers of labeled samples (100, 600, 1000, 3000).
   - Compares the results with the baseline MNIST dataset.

2. **GAN and WGAN for Image Generation** 🖼️🔍:
   - Implements a Deep Convolutional Generative Adversarial Network (DCGAN) and a Wasserstein GAN (WGAN) with Gradient Penalty.
   - Trains the GAN and WGAN models on the FashionMNIST dataset.
   - Generates new images using the trained models and compares the quality of the generated images.
   - Discusses the advantages of the WGAN approach over the traditional GAN.

## Usage 💻

1. **VAE for Semi-Supervised Learning** 📈:
   - Ensure the FashionMNIST and MNIST datasets are downloaded and stored in the `data` directory.
   - Run the provided code to train the VAE model and the SVM classifier on the labeled data.
   - The trained models will be saved, and the test accuracies for different numbers of labeled samples will be printed.
   - The code also plots the original and reconstructed images for both MNIST and FashionMNIST.

2. **GAN and WGAN for Image Generation** 🎨:
   - Ensure the FashionMNIST dataset is downloaded and stored in the `data` directory.
   - Run the provided code to train the DCGAN and WGAN models.
   - The trained generator and discriminator models will be saved.
   - The code will display the generated images from both the DCGAN and WGAN models, as well as some real images from the FashionMNIST dataset for comparison.

## Requirements 📋

- Python 3.x
- PyTorch 🔗
- torchvision 🖼️
- scikit-learn 🧠
- matplotlib 📊
- tqdm 🕰️

## Acknowledgments 🙏

The project was based on the following resources:
- [Semi-supervised Learning with Deep Generative Models](https://arxiv.org/abs/1406.5298)
- [Improved Training of Wasserstein GANs](https://arxiv.org/abs/1704.00028)
- [PyTorch GAN Tutorial](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html)
