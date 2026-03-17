# Deep Learning

This folder contains notebooks and projects focused on **deep learning** with neural networks. Projects range from foundational concepts — such as perceptrons and backpropagation — to advanced architectures including convolutional networks (CNNs), recurrent networks (RNNs/LSTMs), and transfer learning.

All notebooks run in **Google Colab** (GPU runtime recommended) — click the badge at the top of any notebook to get started.

---

## Topics Covered

- Feedforward neural networks and backpropagation
- Convolutional Neural Networks (CNNs) for image classification
- Recurrent Neural Networks (RNNs) and LSTMs for sequential data
- Transfer learning with pre-trained models (VGG, ResNet, EfficientNet)
- Regularisation techniques: dropout, batch normalisation, early stopping
- Model training with TensorFlow/Keras and PyTorch

---

## Projects

| Notebook | Description |
|---|---|
| `image_classification_cnn.ipynb` | CNN trained on CIFAR-10 to classify images into 10 categories using TensorFlow/Keras |
| `sentiment_analysis_lstm.ipynb` | LSTM network for binary sentiment classification on the IMDB movie review dataset |
| `transfer_learning_resnet.ipynb` | Fine-tuning a pre-trained ResNet50 for a custom image classification task |
| `time_series_forecasting_lstm.ipynb` | Multivariate time series forecasting using stacked LSTM layers |
| `neural_network_from_scratch.ipynb` | Building and training a feedforward neural network using only NumPy to understand the fundamentals |

---

## How to Run

1. Open any notebook in this folder.
2. Click the **"Open in Colab"** badge at the top of the notebook.
3. For faster training, enable GPU: `Runtime → Change runtime type → GPU`.
4. Run all cells from top to bottom (`Runtime → Run all`).

No local installation is required. All dependencies are installed within the notebook.

---

## Requirements

When running locally, the following packages are used:

```
numpy
matplotlib
tensorflow
torch
torchvision
```

Install them with:

```bash
pip install numpy matplotlib tensorflow torch torchvision
```

---

*Back to [main portfolio](../README.md)*
