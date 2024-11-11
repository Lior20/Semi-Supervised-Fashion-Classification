# 🖼️ DCGAN and WGAN for Fashion MNIST

This project explores the implementation of Deep Convolutional Generative Adversarial Networks (DCGAN) and Wasserstein Generative Adversarial Networks (WGAN) for generating realistic-looking fashion images from the Fashion MNIST dataset.

## 🔍 Overview

The main objectives of this project are:

1. **Implementing DCGAN**: Designing and training a DCGAN model to generate fashion images.
2. **Implementing WGAN with Gradient Penalty**: Developing a WGAN model with gradient penalty to stabilize the training process and improve the quality of generated images.
3. **Comparing the Performance**: Analyzing the differences between DCGAN and WGAN in terms of training stability, image quality, and other metrics.

The project includes the following key components:

- Custom PyTorch modules for the DCGAN and WGAN generators and discriminators.
- Training functions for both DCGAN and WGAN with optional gradient penalty.
- Visualization of real and generated fashion images.
- Calculation of discriminator accuracy to measure the model's performance.

## 🛠️ Setup and Dependencies

This project requires the following dependencies:

- PyTorch
- NumPy
- Matplotlib
- Torchvision

You can install the required packages using pip:

```
pip install -r requirements.txt
```

## 🚀 Usage

1. Clone the repository:

```
git clone https://github.com/your-username/dcgan-wgan-fashion-mnist.git
```

2. Navigate to the project directory:

```
cd dcgan-wgan-fashion-mnist
```

3. Run the main script:

```
python main.py
```

The script will train both the DCGAN and WGAN models on the Fashion MNIST dataset and display the generated images during the training process.

## 📚 Results

The project showcases the following key results:

- DCGAN and WGAN models successfully generate realistic-looking fashion images.
- WGAN with gradient penalty demonstrates more stable training and improved image quality compared to DCGAN.
- The discriminator accuracy is monitored during training, indicating the models' ability to distinguish real from generated images.

## 🔮 Future Improvements

Some potential future improvements for this project include:

- Exploring additional GAN architectures and techniques, such as ProgressiveGAN or StyleGAN.
- Implementing conditional GAN models to generate images with specific fashion attributes.
- Integrating more advanced evaluation metrics, such as Inception Score or Fréchet Inception Distance.
- Applying the GAN models to generate images for other fashion-related datasets.

## 🤝 Contributing

If you'd like to contribute to this project, please feel free to submit a pull request or open an issue. We welcome any feedback, suggestions, or improvements.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
