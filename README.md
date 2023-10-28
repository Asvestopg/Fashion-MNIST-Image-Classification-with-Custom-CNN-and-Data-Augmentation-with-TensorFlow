# Fashion MNIST Image Classification with Custom CNN and Data Augmentation

Achieve 90% Accuracy on the Fashion MNIST dataset with a custom Convolutional Neural Network (CNN) and data augmentation in just 20 training epochs.

## Project Overview

- **Dataset**: The project uses the Fashion MNIST dataset, which consists of 28x28 grayscale images of 10 different fashion items.

- **Custom CNN Model**: A custom CNN architecture is implemented using TensorFlow and Keras, designed to classify Fashion MNIST images.

- **Data Augmentation**: Data augmentation techniques are applied, including rotation, scaling, and flipping, to improve model robustness and generalization.

- **Training**: The model is trained using the Adam optimizer with sparse categorical cross-entropy loss.

## Getting Started

1. **Dataset**: The Fashion MNIST dataset is loaded using TensorFlow. Training and test data are normalized to the range [0, 1] and expanded with an additional channel dimension.

2. **Model Architecture**: The custom CNN model is defined with layers for convolution, batch normalization, max-pooling, and dense layers. Dropout is used for regularization.

3. **Training**: The model is trained using a data generator that applies data augmentation techniques. The training process is visualized with training and validation loss curves.

## Achieved Results

- After 20 training epochs, the custom CNN model achieves an impressive accuracy of 90% on the Fashion MNIST test dataset.

- A confusion matrix and a random wrong prediction example are visualized to provide insight into the model's performance.

---
