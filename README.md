# Fashion-MNIST Adversarial Attack Project

## Overview

This repository contains the code and resources for a project in the course CS3642 - Artificial Intelligence at Kennesaw State University, Spring 2023. The project explores the Fashion-MNIST dataset, trains a neural network for one-vs-one classification, and investigates adversarial attacks to assess the network's vulnerabilities.

## Key Components

### 1. Dataset Exploration

The Fashion-MNIST dataset, comprising 60,000 training examples of 28x28 black-and-white images and 10 classes, is utilized. The dataset is downloaded using TensorFlow and processed specifically for distinguishing between t-shirts and sneakers.

### 2. Neural Network Training

A simple neural network with two hidden layers and one output linear layer is defined and trained using TensorFlow. The model is trained to classify images into two classes: t-shirts and sneakers.

### 3. Adversarial Attack

An adversarial attack is simulated by applying perturbations to an image of a sneaker, tricking the neural network into misclassifying it as a t-shirt. The project delves into the impact of this noise on the network's predictions.

## Usage

To run the code in this repository, follow these steps:

1. Install the required libraries using the following command:
   ```bash
   pip install tensorflow numpy matplotlib
   ```

2. Download the Fashion-MNIST dataset from the provided links or use the TensorFlow code snippet in the comments.

3. Run the Jupyter notebook or script to execute the code and observe the results.

## Files

- **project.ipynb:** Jupyter notebook containing the project code.
- **data/fmnist:** Pickled Fashion-MNIST dataset.
- **output/:** Directory containing saved images and visualizations generated during the project.
- **README.md:** Readme file providing an overview of the project, instructions for usage, and additional details.

## Note

Make sure to check the answers to the questions at the end of the notebook for a comprehensive understanding of the project's concepts.

## Author

[Hafiz Ans]

## Contact

[anssabrar11@gmail,com]

Feel free to explore and enhance the project for further understanding or use it as a foundation for related tasks.
