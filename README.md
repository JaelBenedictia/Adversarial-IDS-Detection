# Adversarially Robust Intrusion Detection System using CNN and GAN
## Overview

This project focuses on enhancing the robustness of Intrusion Detection Systems (IDS) against adversarial attacks. It leverages Convolutional Neural Networks (CNNs) for classification and Generative Adversarial Networks (GANs) for generating adversarial-like samples to improve model resilience.

## Problem Statement

Deep learning-based IDS models are vulnerable to adversarial attacks such as the Fast Gradient Sign Method (FGSM), where small perturbations in input data can lead to misclassification of malicious traffic as benign.

## Proposed Approach
CNN is used for feature extraction and intrusion detection
FGSM is applied to generate adversarial samples
GAN is trained to produce realistic attack data
Augmented dataset improves the robustness of the IDS model

## Technologies Used
Python, TensorFlow/Keras, NumPy, Pandas, Scikit-learn

## Key Outcomes
Improved detection performance under adversarial conditions
Increased model robustness
Reduced misclassification of malicious inputs
Project Structure
dataset/
models/
src/
results/
project report

## Author
Jael Benedictia
Department of Electronics and Communication Engineering

## Note
Refer to the project report included in the repository for detailed methodology, implementation, and results.
