# Digit Recognizer - Kaggle Competition

## Overview
This repository contains the implementation of the `DigitNet` model, a deep convolutional neural network designed to recognize handwritten digits. The model was developed for the [Digit Recognizer competition on Kaggle](https://www.kaggle.com/competitions/digit-recognizer/overview). The competition is based on the classic machine learning problem of digit recognition using the MNIST dataset.

## Model Architecture
The `DigitNet` model is built using PyTorch and consists of multiple convolutional layers followed by max pooling and fully connected layers. Here's a brief overview of the architecture:

- **Convolutional Layers**: The model starts with two blocks of convolutional layers. Each block consists of two convolutional layers followed by a max pooling layer to reduce spatial dimensions and capture important features.
- **Expanded Convolution**: After initial blocks, the model includes an additional convolutional layer with an increased number of filters, followed by another max pooling step.
- **Fully Connected Layers**: The output from the convolutional layers is flattened and passed through two fully connected layers. The final layer outputs the class logits for each digit (0-9).

## Performance
The `DigitNet` model achieved a score of **0.98764** on the competition leaderboard, which demonstrates its high accuracy in recognizing handwritten digits.

## Usage
To run this model:
1. Ensure you have PyTorch installed and configured, ideally with CUDA support for GPU acceleration.
2. Clone this repository and navigate to the directory.
3. Run the model training and evaluation script (details on the script setup and commands can be added here based on your repo's structure).

## Requirements
- Python 3.x
- PyTorch
- CUDA (optional for GPU acceleration)

## Contributions
Contributions to improve the model or extend its functionality are welcome. Please feel free to fork this repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to Kaggle for hosting the competition and providing the dataset.
- The model architecture was inspired by several research papers on deep learning and computer vision.

## Contact
For any questions, feel free to open an issue in this repository or contact [your GitHub username].

