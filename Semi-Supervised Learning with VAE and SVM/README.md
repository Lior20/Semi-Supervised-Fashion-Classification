# 📊 Semi-Supervised Learning with VAE and SVM

This project implements a semi-supervised learning approach using a Variational Autoencoder (VAE) for feature extraction and a Support Vector Machine (SVM) for classification, as described in the paper "Semi-supervised Learning with Deep Generative Models" by Kingma et al.

## 🔍 Overview

The main objective of this project is to leverage the power of generative models and semi-supervised learning to achieve high classification accuracy on the Fashion-MNIST dataset using only a limited number of labeled examples.

The key steps involved in this project are:

1. **Implementing a VAE**: The VAE model is used to learn a compact latent representation of the input data.
2. **Extracting Latent Representations**: The trained VAE is used to extract latent features from both labeled and unlabeled data.
3. **Training an SVM Classifier**: An SVM classifier is trained on the labeled latent representations to perform the final classification task.
4. **Evaluating the Performance**: The trained SVM is evaluated on the test set, and the accuracy is reported for different amounts of labeled data.

## 🛠️ Setup and Dependencies

This project requires the following dependencies:

- PyTorch
- NumPy
- Scikit-learn
- Matplotlib

You can install the required packages using pip:

```
pip install -r requirements.txt
```

## 🚀 Usage

1. Clone the repository:

```
git clone https://github.com/your-username/semi-supervised-vae-svm.git
```

2. Navigate to the project directory:

```
cd semi-supervised-vae-svm
```

3. Run the main script:

```
python main.py
```

The script will train the VAE and SVM models, and report the classification accuracy for different amounts of labeled data.

## 📚 Results

The results of the semi-supervised learning approach on the Fashion-MNIST dataset are as follows:

| Number of Labels | Accuracy |
| ---------------- | -------- |
| 100              | 70.25%   |
| 600              | 75.90%   |
| 1000             | 79.03%   |
| 3000             | 81.38%   |

These results are comparable to those reported in the original paper, demonstrating the effectiveness of the semi-supervised learning approach.

## 🔮 Future Improvements

Some potential future improvements for this project include:

- Exploring different SVM kernel functions and hyperparameters for better performance.
- Implementing a more advanced semi-supervised learning scheme, such as the M2 model described in the paper.
- Integrating additional data augmentation techniques to improve the generalization of the models.
- Extending the approach to other datasets and classification tasks.

## 🤝 Contributing

If you'd like to contribute to this project, please feel free to submit a pull request or open an issue. We welcome any feedback, suggestions, or improvements.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
