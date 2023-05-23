# MNIST Ensemble Classifier

This GitHub repository contains an experimental implementation of an ensemble classifier for the popular MNIST problem. The ensemble classifier utilizes 15 weak classifiers and employs a voting mechanism to classify instances. This approach aims to leverage the power of ensemble models, which have been shown to provide promising results in various machine learning tasks.
![image](https://github.com/lakshmi-shravya/MNIST_ensemble_model/assets/89875894/113df2f3-8214-4459-8229-0175410201ec)


## MNIST Dataset

The MNIST dataset is a widely used benchmark dataset in the field of computer vision and machine learning. It consists of a large collection of handwritten digits (0-9) represented as 28x28 pixel images. The goal is to accurately classify these digits based on their pixel values. The data is also augmented to increase the size of the dataset that is used to traint the classifiers.

## Ensemble Classifier Approach

The ensemble classifier implemented in this repository takes an experimental approach to solving the MNIST problem. Instead of relying on a single classifier, it combines the predictions of 15 weak classifiers using a voting mechanism. Each weak classifier is trained independently on a subset of the MNIST dataset and contributes its prediction to the final decision.Ensemble models provide improved accuracy by combining multiple weak classifiers. They are robust to overfitting, stable across different datasets, and make better decisions through the voting mechanism. The experimental MNIST Ensemble Classifier in this repository leverages these advantages to enhance the accuracy of digit classification.
